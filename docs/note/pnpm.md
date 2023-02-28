# pnpm

## 1. 全局下载安装最新 pnpm

```
npm i -g pnpm
```

## 2. 安装依赖包

```
pnpm add [package]
pnpm add [package]@[version]
```

## 3. 全局安装依赖

```
pnpm add -g [package]
```

## 4. 将依赖项添加到不同依赖项类别中

```
pnpm add [package]
pnpm add [package] -D
```

## 5. 移除依赖包

```
pnpm remove [package]
```

## 6. 安装项目的全部依赖

```
pnpm i
```

## 7. 登录 npm registry

```
pnpm login
```

## 8. 退出 npm registry

```
pnpm logout
```

## 9. 发布 npm 包

```
pnpm publish
```

## 10. 使用淘宝源

```
pnpm config set registry https://registry.npmmirror.com
pnpm get registry
```

## 11. 改回npm源

```
pnpm config set registry https://registry.npmjs.org
```

## 12. 查看全局包

```
pnpm list -g
```

## 13. 更新包

```
pnpm upgrade [package]
```
