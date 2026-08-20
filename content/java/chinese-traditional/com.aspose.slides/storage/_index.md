---
title: Storage
second_title: Aspose.Slides for Java API 參考手冊
description: 代表用於 . 的暫時性資料儲存。
type: docs
url: /zh-hant/com.aspose.slides/storage/
---
**繼承:**
java.lang.Object
```
public final class Storage
```

代表 [WebDocument](../../com.aspose.slides/webdocument) 的暫時性資料儲存。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [Storage()](#Storage--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Puts the value into the storage. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Gets the data from the storage. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines whether the storage contains an element with the specified key. |

### Storage() {#Storage--}
```
public Storage()
```

### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

將值放入儲存空間。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | java.lang.String | 值的鍵。 |
| value | TValue | 值。 |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

從儲存空間取得資料。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | java.lang.String | 值的鍵。 |

**傳回:**
TValue - 若資料集合中存在則傳回資料值，否則傳回 null。

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

判斷儲存空間是否包含具有指定鍵的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | java.lang.String | 值的鍵。 |

**傳回:**
boolean - 若儲存空間包含具有指定鍵的元素則傳回 true，否則傳回 false。