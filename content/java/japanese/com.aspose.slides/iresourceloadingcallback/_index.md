---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API リファレンス
description: 外部リソースの読み込みを管理するために使用されるコールバックインターフェイス。
type: docs
url: /ja/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

外部リソースの読み込みを管理するために使用されるコールバックインターフェイス。

## Methods

| Method | Description |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | 外部リソースの読み込みを調整するコールバックメソッド。 |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

外部リソースの読み込みを調整するコールバックメソッド。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | 読み込みリソースデータ [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs)。 |

**戻り値:**
int - リソース読み込みの判断 [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction)。