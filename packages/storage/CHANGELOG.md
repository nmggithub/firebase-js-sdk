#Unreleased

## 0.9.0

### Minor Changes

- [`e34e98e73`](https://github.com/firebase/firebase-js-sdk/commit/e34e98e73a72f77ee87d9005d6728402129deda9) [#5672](https://github.com/firebase/firebase-js-sdk/pull/5672) (fixes [#76](https://github.com/firebase/firebase-js-sdk/issues/76)) - Adds `getBytes()`, `getStream()` and `getBlob()`, which allow direct file downloads from the SDK.

### Patch Changes

- [`0394cc97b`](https://github.com/firebase/firebase-js-sdk/commit/0394cc97b98f04dae87b718655eb46174275ebc2) [#5743](https://github.com/firebase/firebase-js-sdk/pull/5743) - Fix typings for storage and storage-compat.

## 0.8.7

### Patch Changes

- [`e0fe2b668`](https://github.com/firebase/firebase-js-sdk/commit/e0fe2b668b64b64d842988c2c147d3de66148f48) [#5703](https://github.com/firebase/firebase-js-sdk/pull/5703) (fixes [#5628](https://github.com/firebase/firebase-js-sdk/issues/5628)) - Clear the global timeout once an operation is done in the Storage SDK. Otherwise it may prevent Node.js from exiting.

## 0.8.6

### Patch Changes

- [`3281315fa`](https://github.com/firebase/firebase-js-sdk/commit/3281315fae9c6f535f9d5052ee17d60861ea569a) [#5708](https://github.com/firebase/firebase-js-sdk/pull/5708) (fixes [#1487](https://github.com/firebase/firebase-js-sdk/issues/1487)) - Update build scripts to work with the exports field

- Updated dependencies [[`3281315fa`](https://github.com/firebase/firebase-js-sdk/commit/3281315fae9c6f535f9d5052ee17d60861ea569a)]:
  - @firebase/component@0.5.9
  - @firebase/util@1.4.2

## 0.8.5

### Patch Changes

- [`2322b6023`](https://github.com/firebase/firebase-js-sdk/commit/2322b6023c628cd9f4f4172767c17d215dd91684) [#5693](https://github.com/firebase/firebase-js-sdk/pull/5693) - Add exports field to all packages

- Updated dependencies [[`2322b6023`](https://github.com/firebase/firebase-js-sdk/commit/2322b6023c628cd9f4f4172767c17d215dd91684)]:
  - @firebase/component@0.5.8
  - @firebase/util@1.4.1

## 0.8.4

### Patch Changes

- [`a7e00b9eb`](https://github.com/firebase/firebase-js-sdk/commit/a7e00b9ebbb05b094a8bf620790146e750463c12) [#5578](https://github.com/firebase/firebase-js-sdk/pull/5578) (fixes [#5372](https://github.com/firebase/firebase-js-sdk/issues/5372)) - Do not throw from `connection.send` to enable retries in Node.js.

* [`93795c780`](https://github.com/firebase/firebase-js-sdk/commit/93795c7801d6b28ccbbe5855fd2f3fc377b1db5f) [#5596](https://github.com/firebase/firebase-js-sdk/pull/5596) - report build variants for packages

## 0.8.3

### Patch Changes

- Updated dependencies [[`a99943fe3`](https://github.com/firebase/firebase-js-sdk/commit/a99943fe3bd5279761aa29d138ec91272b06df39), [`b835b4cba`](https://github.com/firebase/firebase-js-sdk/commit/b835b4cbabc4b7b180ae38b908c49205ce31a422)]:
  - @firebase/util@1.4.0
  - @firebase/component@0.5.7

## 0.8.2

### Patch Changes

- [`66d4a1e5d`](https://github.com/firebase/firebase-js-sdk/commit/66d4a1e5d8e1b8b952e21fc3190ec7076d8161ea) [#5453](https://github.com/firebase/firebase-js-sdk/pull/5453) - Store protocol and host separately on Storage service instance. Fixes a bug when generating url strings.

## 0.8.1

### Patch Changes

- [`6163bb282`](https://github.com/firebase/firebase-js-sdk/commit/6163bb282b4e3b6fe5f405c3b3e35d5691d41677) [#5399](https://github.com/firebase/firebase-js-sdk/pull/5399) - Addressed incorrect use of the `node-fetch` polyfill

## 0.8.0

### Minor Changes

- [`cdada6c68`](https://github.com/firebase/firebase-js-sdk/commit/cdada6c68f9740d13dd6674bcb658e28e68253b6) [#5345](https://github.com/firebase/firebase-js-sdk/pull/5345) (fixes [#5015](https://github.com/firebase/firebase-js-sdk/issues/5015)) - Release modularized SDKs

## 0.7.0

### Minor Changes

- [`3c6a11c8d`](https://github.com/firebase/firebase-js-sdk/commit/3c6a11c8d0b35afddb50e9c3e0c4d2e30f642131) [#5282](https://github.com/firebase/firebase-js-sdk/pull/5282) - Implement mockUserToken for Storage and fix JWT format bugs.

### Patch Changes

- [`fbb32e7bf`](https://github.com/firebase/firebase-js-sdk/commit/fbb32e7bff32942bea16385fc387b8c22952ed4d) [#5315](https://github.com/firebase/firebase-js-sdk/pull/5315) (fixes [#5180](https://github.com/firebase/firebase-js-sdk/issues/5180)) - Change `ref()` to not throw if given a path with '..' in it.

- Updated dependencies [[`bb6b5abff`](https://github.com/firebase/firebase-js-sdk/commit/bb6b5abff6f89ce9ec1bd66ff4e795a059a98eec), [`3c6a11c8d`](https://github.com/firebase/firebase-js-sdk/commit/3c6a11c8d0b35afddb50e9c3e0c4d2e30f642131)]:
  - @firebase/component@0.5.6
  - @firebase/storage-types@0.5.0
  - @firebase/util@1.3.0

## 0.6.2

### Patch Changes

- [`5bda08eee`](https://github.com/firebase/firebase-js-sdk/commit/5bda08eee4e0c4007b1d858edcbcc8020604d560) [#5245](https://github.com/firebase/firebase-js-sdk/pull/5245) - Adds a browser CJS build as ./dist/index.browser.cjs.js.

## 0.6.1

### Patch Changes

- Updated dependencies [[`a3cbe719b`](https://github.com/firebase/firebase-js-sdk/commit/a3cbe719b1bd733a5c4c15ee0d0e6388d512054c)]:
  - @firebase/util@1.2.0
  - @firebase/component@0.5.5

## 0.6.0

### Minor Changes

- [`b3caa5158`](https://github.com/firebase/firebase-js-sdk/commit/b3caa515846d2bfcf4a95dedff69f08d503cbfc2) [#5149](https://github.com/firebase/firebase-js-sdk/pull/5149) - Add NodeJS support to Cloud Storage for Firebase. This release changes the `main` field in package.json to point to a Node specific build. If you are building a bundle for borwser usage, please make sure that your bundler uses the `browser` field (the default).

## 0.5.6

### Patch Changes

- Updated dependencies [[`56a6a9d4a`](https://github.com/firebase/firebase-js-sdk/commit/56a6a9d4af2766154584a0f66d3c4d8024d74ba5)]:
  - @firebase/component@0.5.4

## 0.5.5

### Patch Changes

- Updated dependencies [[`725ab4684`](https://github.com/firebase/firebase-js-sdk/commit/725ab4684ef0999a12f71e704c204a00fb030e5d)]:
  - @firebase/component@0.5.3

## 0.5.4

### Patch Changes

- Updated dependencies [[`4c4b6aed9`](https://github.com/firebase/firebase-js-sdk/commit/4c4b6aed9757c9a7e75fb698a15e53274f93880b)]:
  - @firebase/component@0.5.2

## 0.5.3

### Patch Changes

- Updated dependencies [[`5fbc5fb01`](https://github.com/firebase/firebase-js-sdk/commit/5fbc5fb0140d7da980fd7ebbfbae810f8c64ae19)]:
  - @firebase/component@0.5.1

## 0.5.2

### Patch Changes

- Updated dependencies [[`c34ac7a92`](https://github.com/firebase/firebase-js-sdk/commit/c34ac7a92a616915f38d192654db7770d81747ae), [`ac4ad08a2`](https://github.com/firebase/firebase-js-sdk/commit/ac4ad08a284397ec966e991dd388bb1fba857467)]:
  - @firebase/component@0.5.0
  - @firebase/util@1.1.0

## 0.5.1

### Patch Changes

- [`364e336a0`](https://github.com/firebase/firebase-js-sdk/commit/364e336a04e419d019846d702cf27144aeb8939e) [#4807](https://github.com/firebase/firebase-js-sdk/pull/4807) - Fix infinite recursion caused by `FirebaseStorageError` message getter.

- Updated dependencies [[`3f370215a`](https://github.com/firebase/firebase-js-sdk/commit/3f370215aa571db6b41b92a7d8a9aaad2ea0ecd0)]:
  - @firebase/storage-types@0.4.1

## 0.5.0

### Minor Changes

- [`5ae73656d`](https://github.com/firebase/firebase-js-sdk/commit/5ae73656d976fa724ea6ca86d496e9531c95b29c) [#4346](https://github.com/firebase/firebase-js-sdk/pull/4346) - Add `storage().useEmulator()` method to enable emulator mode for storage, allowing users
  to set a storage emulator host and port.

### Patch Changes

- Updated dependencies [[`7354a0ed4`](https://github.com/firebase/firebase-js-sdk/commit/7354a0ed438f4e3df6577e4927e8c8f8f1fbbfda), [`5ae73656d`](https://github.com/firebase/firebase-js-sdk/commit/5ae73656d976fa724ea6ca86d496e9531c95b29c)]:
  - @firebase/util@1.0.0
  - @firebase/storage-types@0.4.0
  - @firebase/component@0.4.1

## 0.4.7

### Patch Changes

- Updated dependencies [[`f24d8961b`](https://github.com/firebase/firebase-js-sdk/commit/f24d8961b3b87821413297688803fc85113086b3)]:
  - @firebase/component@0.4.0

## 0.4.6

### Patch Changes

- Updated dependencies [[`de5f90501`](https://github.com/firebase/firebase-js-sdk/commit/de5f9050137acc9ed1490082e5aa429b5de3cb2a)]:
  - @firebase/util@0.4.1
  - @firebase/component@0.3.1

## 0.4.5

### Patch Changes

- [`5c1a83ed7`](https://github.com/firebase/firebase-js-sdk/commit/5c1a83ed70bae979322bd8751c0885d683ce4bf3) [#4595](https://github.com/firebase/firebase-js-sdk/pull/4595) - Component facotry now takes an options object. And added `Provider.initialize()` that can be used to pass an options object to the component factory.

- Updated dependencies [[`5c1a83ed7`](https://github.com/firebase/firebase-js-sdk/commit/5c1a83ed70bae979322bd8751c0885d683ce4bf3)]:
  - @firebase/component@0.3.0

## 0.4.4

### Patch Changes

- Updated dependencies [[`ec95df3d0`](https://github.com/firebase/firebase-js-sdk/commit/ec95df3d07e5f091f2a7f7327e46417f64d04b4e)]:
  - @firebase/util@0.4.0
  - @firebase/component@0.2.1

## 0.4.3

### Patch Changes

- Updated dependencies [[`6afe42613`](https://github.com/firebase/firebase-js-sdk/commit/6afe42613ed3d7a842d378dc1a09a795811db2ac)]:
  - @firebase/component@0.2.0

## 0.4.2

### Patch Changes

- [`f9dc50e35`](https://github.com/firebase/firebase-js-sdk/commit/f9dc50e3520d50b70eecd28b81887e0053f9f636) [#3499](https://github.com/firebase/firebase-js-sdk/pull/3499) - Refactored Storage to allow for modularization.

## 0.4.1

### Patch Changes

- Updated dependencies [[`9cf727fcc`](https://github.com/firebase/firebase-js-sdk/commit/9cf727fcc3d049551b16ae0698ac33dc2fe45ada)]:
  - @firebase/util@0.3.4
  - @firebase/component@0.1.21

## 0.4.0

### Minor Changes

- [`b247ffa76`](https://github.com/firebase/firebase-js-sdk/commit/b247ffa760aec1636de6cfc78851f97a840181ae) [#3967](https://github.com/firebase/firebase-js-sdk/pull/3967) - This releases removes all input validation. Please use our TypeScript types to validate API usage.

### Patch Changes

- Updated dependencies [[`a5768b0aa`](https://github.com/firebase/firebase-js-sdk/commit/a5768b0aa7d7ce732279931aa436e988c9f36487), [`7d916d905`](https://github.com/firebase/firebase-js-sdk/commit/7d916d905ba16816ac8ac7c8748c83831ff614ce)]:
  - @firebase/component@0.1.20
  - @firebase/util@0.3.3

## 0.3.43

### Patch Changes

- Updated dependencies [[`da1c7df79`](https://github.com/firebase/firebase-js-sdk/commit/da1c7df7982b08bbef82fcc8d93255f3e2d23cca), [`fb3b095e4`](https://github.com/firebase/firebase-js-sdk/commit/fb3b095e4b7c8f57fdb3172bc039c84576abf290)]:
  - @firebase/component@0.1.19
  - @firebase/util@0.3.2

## 0.3.42

### Patch Changes

- Updated dependencies [[`d4ca3da0`](https://github.com/firebase/firebase-js-sdk/commit/d4ca3da0a59fcea1261ba69d7eb663bba38d3089)]:
  - @firebase/util@0.3.1
  - @firebase/component@0.1.18

## 0.3.41

### Patch Changes

- Updated dependencies [[`a87676b8`](https://github.com/firebase/firebase-js-sdk/commit/a87676b84b78ccc2f057a22eb947a5d13402949c)]:
  - @firebase/util@0.3.0
  - @firebase/component@0.1.17

## 0.3.40

### Patch Changes

- [`ee33ebf7`](https://github.com/firebase/firebase-js-sdk/commit/ee33ebf726b1dc31ab4817e7a1923f7b2757e17c) [#3414](https://github.com/firebase/firebase-js-sdk/pull/3414) - Error messages for backend errors now include the backend's reponse message.

## 0.3.39

### Patch Changes

- [`9c409ea7`](https://github.com/firebase/firebase-js-sdk/commit/9c409ea74efd00fe17058c5c8b74450fae67e9ee) [#3224](https://github.com/firebase/firebase-js-sdk/pull/3224) Thanks [@schmidt-sebastian](https://github.com/schmidt-sebastian)! - [fix] Updated the TypeScript types for all APIs using Observers to allow callback omission.

- Updated dependencies [[`9c409ea7`](https://github.com/firebase/firebase-js-sdk/commit/9c409ea74efd00fe17058c5c8b74450fae67e9ee)]:
  - @firebase/storage-types@0.3.13

## 0.3.38

### Patch Changes

- Updated dependencies [[`a754645e`](https://github.com/firebase/firebase-js-sdk/commit/a754645ec2be1b8c205f25f510196eee298b0d6e)]:
  - @firebase/component@0.1.16
- [Changed] Added an additional header to all network requests that propagates the Firebase App ID.

# 6.1.0

- [Feature] Added the support for List API.
