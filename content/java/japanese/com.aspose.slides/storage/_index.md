---
title: Storage
second_title: Aspose.Slides for Java API リファレンス
description: 一時的なデータストレージを表します。
type: docs
url: /ja/com.aspose.slides/storage/
---
**継承:**
java.lang.Object
```
public final class Storage
```

一時的なデータストレージを表します [WebDocument](../../com.aspose.slides/webdocument)。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Storage()](#Storage--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | 値をストレージに格納します。 |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | ストレージからデータを取得します。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | ストレージに指定されたキーの要素が含まれているかどうかを判定します。 |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


値をストレージに格納します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | 値のキー。 |
| value | TValue | 値。 |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


ストレージからデータを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | 値のキー。 |

**戻り値:**
TValue - データコレクションに存在すればデータ値を返し、存在しなければ null を返します。
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


ストレージに指定されたキーの要素が含まれているかどうかを判定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | 値のキー。 |

**戻り値:**
boolean - ストレージに指定されたキーの要素が含まれていれば true、そうでなければ false を返します。