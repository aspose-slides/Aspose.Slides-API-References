---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 外部リソースのロードを管理するために使用されるコールバックインターフェイスです。
type: docs
url: /ja/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

外部リソースのロードを管理するために使用されるコールバックインターフェイスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | 外部リソースのロードを制御するコールバックメソッドです。 |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


外部リソースのロードを制御するコールバックメソッドです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | ローディングリソースデータ [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs)。 |

**戻り値:**
int - リソースロードの判断 [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction)。