---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: 外部リソース読み込み引数のインターフェイス。
type: docs
url: /ja/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

外部リソース読み込み引数のインターフェイスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | インポートされたプレゼンテーションで指定されたリソースの元の URI。 |
| [getUri()](#getUri--) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) が [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) を返す場合にダウンロードに使用されるリソースの URI。 |
| [setUri(String value)](#setUri-java.lang.String-) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) が [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) を返す場合にダウンロードに使用されるリソースの URI。 |
| [setData(byte[] data)](#setData-byte---) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) が [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) を返す場合に使用されるリソースのユーザー提供データを設定します。 |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


インポートされたプレゼンテーションで指定されたリソースの元の URI。

**戻り値:**  
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) が [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) を返す場合にダウンロードに使用されるリソースの URI。初期状態ではリソースの元の URI に設定されていますが、任意の値に再定義可能です。

**戻り値:**  
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) が [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) を返す場合にダウンロードに使用されるリソースの URI。初期状態ではリソースの元の URI に設定されていますが、任意の値に再定義可能です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) が [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) を返す場合に使用されるリソースのユーザー提供データを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | リソースの提供されたデータ byte[] |