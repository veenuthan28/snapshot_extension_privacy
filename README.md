# Privacy Policy — SnapShot

SnapShot does **not** collect, store, or transmit any user data to external servers. All data (screenshots and annotations) is stored **locally** in your browser using `chrome.storage.local`. No information is sent to any external server or third-party service.

## Permissions Used

| Permission  | Purpose                                                                 |
| ----------- | ----------------------------------------------------------------------- |
| `activeTab` | Access the current tab to capture a screenshot                          |
| `debugger`  | Attach Chrome DevTools Protocol for pixel-perfect full-page screenshots |
| `storage`   | Temporarily store screenshot data between capture & editor              |
| `tabs`      | Open the annotation editor in a new tab                                 |

## Network Requests

This extension makes **zero** network requests. All processing happens entirely on your device. Screenshots are captured via Chrome's native `chrome.debugger` API (DevTools Protocol), stored briefly in local storage, and displayed in the editor — nothing ever leaves your machine.
