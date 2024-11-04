# ESLint config

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint eslint-config-next @riadyounes/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@riadyounes/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @riadyounes/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@riadyounes/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @riadyounes/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@riadyounes/eslint-config/node"
}
```