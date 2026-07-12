---
title: VbaProjectFactory
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: COM インターフェイスを介して VBA プロジェクトを作成できます
type: docs
url: /ja/com.aspose.slides/vbaprojectfactory/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

COM インターフェイスを介して VBA プロジェクトを作成できます
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA プロジェクト ファクトリの静的インスタンス。 |
| [createVbaProject()](#createVbaProject--) | 新しい VBA プロジェクトを作成します。 |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLE コンテナから VBA プロジェクトを読み取ります。 |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA プロジェクト ファクトリの静的インスタンス。 読み取り専用 [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)。

**戻り値:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


新しい VBA プロジェクトを作成します。

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 新しい VBA プロジェクト
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


OLE コンテナから VBA プロジェクトを読み取ります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] |  |

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 読み取った VBA プロジェクト