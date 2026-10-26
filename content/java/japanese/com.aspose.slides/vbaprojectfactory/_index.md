---
title: VbaProjectFactory
second_title: Aspose.Slides for Java APIリファレンス
description: COMインターフェイスを介してVBAプロジェクトを作成できます
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

COMインターフェイスを介してVBAプロジェクトを作成できます
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInstance()](#getInstance--) | VBAプロジェクトファクトリの静的インスタンス。 |
| [createVbaProject()](#createVbaProject--) | 新しいVBAプロジェクトを作成します。 |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLEコンテナからVBAプロジェクトを読み取ります。 |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBAプロジェクトファクトリの静的インスタンス。読み取り専用 [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)。

**戻り値:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


新しいVBAプロジェクトを作成します。

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 新しいVBAプロジェクト
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


OLEコンテナからVBAプロジェクトを読み取ります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] |  |

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - VBAプロジェクトを読み取ります