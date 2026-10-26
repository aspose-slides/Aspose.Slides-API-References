---
title: ICustomXmlPart
second_title: Aspose.Slides for Java APIリファレンス
description: カスタム XML パートを表します。
type: docs
url: /ja/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

カスタム XML パートを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Returns or sets xml data as UTF-8 string. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Returns or sets xml data as UTF-8 string. |
| [getXmlData()](#getXmlData--) | Returns or sets xml data. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Returns or sets xml data. |
| [getItemId()](#getItemId--) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Returns the collection XML schemas that are associated with the custom XML part. |
| [remove()](#remove--) | Removes the custom xml part from the presentation. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

XML データを UTF-8 文字列として取得または設定します。 読み取り/書き込み String。

**戻り値:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

XML データを UTF-8 文字列として取得または設定します。 読み取り/書き込み String。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

XML データを取得または設定します。 読み取り/書き込み byte[]。

**戻り値:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

XML データを取得または設定します。 読み取り/書き込み byte[]。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Office Open XML ドキュメント内の単一のカスタム XML パートを一意に識別するグローバルにユニークな識別子 (GUID) を指定します。 読み取り専用 java.util.UUID。

**戻り値:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Office Open XML ドキュメント内の単一のカスタム XML パートを一意に識別するグローバルにユニークな識別子 (GUID) を指定します。 読み取り専用 java.util.UUID。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

カスタム XML パートに関連付けられたコレクション XML スキーマを返します。 読み取り専用 String[]。

**戻り値:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

プレゼンテーションからカスタム XML パートを削除します。