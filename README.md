# GitHub 图床 (Images)

个人 GitHub 图床仓库，主要配合 PicGo 等工具用于博客、文档及静态图片资源托管。

## 引用方式

### 1. GitHub Raw
```text
https://raw.githubusercontent.com/patrick12138/images/main/<path-to-image>
```

示例：
```text
https://raw.githubusercontent.com/patrick12138/images/main/Avatar.png
```

### 2. CDN 加速 (jsDelivr)
```text
https://cdn.jsdelivr.net/gh/patrick12138/images@main/<path-to-image>
```

示例：
```text
https://cdn.jsdelivr.net/gh/patrick12138/images@main/Avatar.png
```

## PicGo 配置参考

- **设定仓库名**: `patrick12138/images`
- **设定分支名**: `main`
- **设定存储路径**: 自定义（如留空表示根目录，或填写 `img/`）
- **设定自定义域名**: `https://cdn.jsdelivr.net/gh/patrick12138/images@main`（或根据需要使用 GitHub Raw）
