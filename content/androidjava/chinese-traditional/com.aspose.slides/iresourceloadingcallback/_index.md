---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 用於管理外部資源載入的回呼介面。
type: docs
url: /zh-hant/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

用於管理外部資源載入的回呼介面。

## 方法

| 方法 | 說明 |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | 調節外部資源載入的回呼方法。 |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

調節外部資源載入的回呼方法。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | 載入資源資料 [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs)。 |

**回傳值：**
int - 資源載入決策 [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction)。