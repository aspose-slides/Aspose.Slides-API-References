---
title: OleEmbeddedDataInfo
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: OLE オブジェクトの埋め込みデータ情報を表します。
type: docs
url: /ja/com.aspose.slides/oleembeddeddatainfo/
---
**継承:**
java.lang.Object

**実装されたインターフェイス:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

OLE オブジェクトの埋め込みデータ情報を表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | OLE オブジェクトの新しい埋め込みデータ情報を作成します。 |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | OLE オブジェクトの埋め込みデータ情報の新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 埋め込み OLE オブジェクトのファイルデータを取得します。読み取り専用 byte[]。 |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 現在の埋め込み OLE オブジェクトのファイル拡張子を取得します。読み取り専用 String。 |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

OLE オブジェクトの新しい埋め込みデータ情報を作成します。

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

埋め込み OLE オブジェクトのデータ情報の新しいインスタンスを作成します。

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| embeddedFileData | byte[] | 埋め込み OLE オブジェクトのファイルデータ byte[]。 |
| embeddedFileExtension | java.lang.String | 現在の埋め込み OLE オブジェクトのファイル拡張子 String。 |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

埋め込み OLE オブジェクトのファイルデータを取得します。読み取り専用 byte[]。

**戻り値:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

現在の埋め込み OLE オブジェクトのファイル拡張子を取得します。読み取り専用 String。

**戻り値:**
java.lang.String