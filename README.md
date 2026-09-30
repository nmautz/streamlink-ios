# StreamLink for iOS

The SideStore / AltStore source for the StreamLink iOS app.

## Install

1. Install [SideStore](https://sidestore.io) (or AltStore) on your iPhone.
2. In SideStore open **Sources**, tap **+**, and add:

   ```
   https://raw.githubusercontent.com/nmautz/streamlink-ios/main/apps.json
   ```

3. Open the StreamLink source and install **StreamLink**. New versions appear
   as updates in SideStore.

StreamLink is a client. It needs your own StreamLink server running at home:
see [nmautz/torrentstreamingtool](https://github.com/nmautz/torrentstreamingtool).

Each `.ipa` is under [Releases](https://github.com/nmautz/streamlink-ios/releases).
It is unsigned, and SideStore signs it with your Apple ID when it installs it.
Other sideloaders such as Sideloadly can install it too.
