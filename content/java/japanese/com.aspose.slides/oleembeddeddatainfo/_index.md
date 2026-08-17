---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Java API リファレンス
description: OLE オブジェクト用の埋め込みデータ情報を表します。
type: docs
url: /ja/com.aspose.slides/oleembeddeddatainfo/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

OLE オブジェクト用の埋め込みデータ情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | 新しい OLE オブジェクト用の埋め込みデータ情報を作成します。 |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | 新しい OLE オブジェクト用の埋め込みデータ情報のインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 埋め込み OLE オブジェクトのファイルデータを返します（読み取り専用 byte[]）。 |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 現在の埋め込み OLE オブジェクトのファイル拡張子を返します（読み取り専用 String）。 |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

新しい OLE オブジェクト用の埋め込みデータ情報を作成します。

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

新しい OLE オブジェクト用の埋め込みデータ情報のインスタンスを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| embeddedFileData | byte[] | 埋め込み OLE オブジェクトのファイルデータ byte[]。 |
| embeddedFileExtension | java.lang.String | 現在の埋め込み OLE オブジェクトのファイル拡張子 String。 |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

埋め込み OLE オブジェクトのファイルデータを返します（読み取り専用 byte[]）。

**戻り値:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

現在の埋め込み OLE オブジェクトのファイル拡張子を返します（読み取り専用 String）。

**戻り値:**
java.lang.String