# docstring-checker-typescript

> Check that all docstrings in a project have been updated to match latest changes, written in Microsoft typed Javascript (Typescript).


## ✨ Features

this is utterly useless. just keep track of the dates in your files manually. if you really want a tool like this, check out e.g. my rust version that is actually useful.


## ⚡ Example usage

run the fil with some form of typescript node version, `ts-node bin/index.ts` , or do some other way, maybe you can compile it first with `tsc` and then just run it with javascript node `node bin/index.js`.

If you have no outdated docstrings in your typescript files you will see:

```
ts-node .\bin\index.ts .

 🎉 You have no outdated docstrings. Great job!
```

Or if you have outdated docstrings you will see:

```
ts-node .\bin\index.ts .

 🧸 You have 1 outdated docstring(s) in total. Resolve these files:
    - src\DocstringChecker.ts
```


## ⚠️ License
docstring-checker-typescript is free and open source software released under the [MIT](./LICENSE) license.
