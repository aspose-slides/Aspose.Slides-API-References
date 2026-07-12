---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API リファレンス
description: COM インターフェイスを使用して VBA プロジェクトを作成できます
type: docs
url: /ja/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

COM インターフェイスを使用して VBA プロジェクトを作成できます
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | 新しい VBA プロジェクトを作成します。 |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

新しい VBA プロジェクトを作成します。

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - New VBA project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

OLE コンテナから VBA プロジェクトを読み取ります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | Ole データ byte[] |

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Read VBA project