# react-router-app
* [Tutorial](https://reactrouter.com/web/guides/quick-start)

## 1. Setup
```bash
$ npx create-react-app react-router-app
$ cd react-router-app/
$ yarn start

$ yarn add react-router-dom
```

### 1.1. Absolute Imports
`jsconfig.json`
```json
{
    "compilerOptions": {
        "baseUrl": "src"
    },
    "include": [
        "src"
    ]
}
```