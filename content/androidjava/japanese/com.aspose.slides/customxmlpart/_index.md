---
title: CustomXmlPart
second_title: Aspose.Slides for Android の Java API リファレンス
description: カスタム XML パートを表します。
type: docs
url: /ja/com.aspose.slides/customxmlpart/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)  
```
public class CustomXmlPart implements ICustomXmlPart
```

カスタム XML パートを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXmlData()](#getXmlData--) | XML データを取得または設定します。 |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML データを取得または設定します。 |
| [getXmlAsString()](#getXmlAsString--) | UTF-8 文字列として XML データを取得または設定します。 |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | UTF-8 文字列として XML データを取得または設定します。 |
| [getItemId()](#getItemId--) | Office Open XML ドキュメント内の単一のカスタム XML パートを一意に識別する、グローバルに一意な識別子 (GUID) を指定します。 |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Office Open XML ドキュメント内の単一のカスタム XML パートを一意に識別する、グローバルに一意な識別子 (GUID) を指定します。 |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | カスタム XML パートに関連付けられたコレクション XML スキーマを返します。 |
| [remove()](#remove--) | プレゼンテーションからカスタム XML パートを削除します。 |

### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


XML データを取得または設定します。読み取り/書き込み byte[].

**戻り値:**
byte[]

### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


XML データを取得または設定します。読み取り/書き込み byte[].

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


UTF-8 文字列として XML データを取得または設定します。読み取り/書き込み String.

**戻り値:**
java.lang.String

### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


UTF-8 文字列として XML データを取得または設定します。読み取り/書き込み String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Office Open XML ドキュメント内の単一のカスタム XML パートを一意に識別する、グローバルに一意な識別子 (GUID) を指定します。読み取り専用 java.util.UUID。

**戻り値:**
java.util.UUID

### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Office Open XML ドキュメント内の単一のカスタム XML パートを一意に識別する、グローバルに一意な識別子 (GUID) を指定します。読み取り専用 java.util.UUID。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


カスタム XML パートに関連付けられたコレクション XML スキーマを返します。読み取り専用 String[]。

**戻り値:**
java.lang.String[]

### remove() {#remove--}
```
public final void remove()
```


プレゼンテーションからカスタム XML パートを削除します。