---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: カスタム XML パートを表します。
type: docs
url: /ja/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

カスタム XML パートを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | XML データを UTF-8 文字列として取得または設定します。 |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | XML データを UTF-8 文字列として取得または設定します。 |
| [getXmlData()](#getXmlData--) | XML データを取得または設定します。 |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML データを取得または設定します。 |
| [getItemId()](#getItemId--) | Office Open XML ドキュメント内で単一のカスタム XML パートを一意に識別するグローバルに一意な識別子（GUID）を指定します。 |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Office Open XML ドキュメント内で単一のカスタム XML パートを一意に識別するグローバルに一意な識別子（GUID）を指定します。 |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | カスタム XML パートに関連付けられたコレクション XML スキーマを取得します。 |
| [remove()](#remove--) | プレゼンテーションからカスタム XML パートを削除します。 |

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

**パラメーター:**
| パラメーター | 型 | 説明 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Office Open XML ドキュメント内で単一のカスタム XML パートを一意に識別するグローバルに一意な識別子（GUID）を取得します。 読み取り専用 java.util.UUID。

**戻り値:**
java.util.UUID

### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Office Open XML ドキュメント内で単一のカスタム XML パートを一意に識別するグローバルに一意な識別子（GUID）を指定します。 読み取り専用 java.util.UUID。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

カスタム XML パートに関連付けられたコレクション XML スキーマを取得します。 読み取り専用 String[]。

**戻り値:**
java.lang.String[]

### remove() {#remove--}
```
public abstract void remove()
```

プレゼンテーションからカスタム XML パートを削除します。