## Setting up

1. Clone this repo and open the directory.
1. Install dependency with `npm install` and then configure it with `npx firebase login`.
1. Install Cloud Functions dependencies locally by running: `npm run setup`

## Run in local

1. Start emulator by `npm run serve`.

If you want to try it in a bworser, open this [link](http://localhost:5001/sample-firebase-20200910/us-central1/addMessage?text=uppercaseme).

## Deploy

1. Deploy the functions by `npm run deploy`.
1. You can see our Functions on the Firebase Console.

## Memo

### If you want to use `firebase-tools` command directly.

Use `npx firebase <any arguments>`.
