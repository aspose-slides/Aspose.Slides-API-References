---
title: Storage
second_title: Aspose.Slides for Android の Java API リファレンス
description: 一時データストレージを表します。
type: docs
url: /ja/com.aspose.slides/storage/
---
**Inheritance:**
java.lang.Object
```
public final class Storage
```

[WebDocument](../../com.aspose.slides/webdocument) 用の一時データストレージを表します。

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Storage()](#Storage--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | ストレージに値を格納します。 |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | ストレージからデータを取得します。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 指定されたキーを持つ要素がストレージに含まれているかどうかを判定します。 |
### Storage() {#Storage--}
```
public Storage()
```

### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

ストレージに値を格納します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | 値のキー。 |
| value | TValue | 値。 |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

ストレージからデータを取得します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | 値のキー。 |

**Returns:**
TValue - データコレクションに存在する場合はデータ値、存在しない場合は null。

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

指定されたキーを持つ要素がストレージに含まれているかどうかを判定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | 値のキー。 |

**Returns:**
boolean - 指定されたキーを持つ要素がストレージに含まれる場合は true、そうでない場合は false。