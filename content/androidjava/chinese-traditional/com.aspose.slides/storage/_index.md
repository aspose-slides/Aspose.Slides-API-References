---
title: Storage
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表一個暫時的資料儲存。
type: docs
url: /zh-hant/com.aspose.slides/storage/
---
**繼承:**  
java.lang.Object  
```
public final class Storage
```

代表一個用於 [WebDocument](../../com.aspose.slides/webdocument) 的暫時資料儲存。

## 建構子

| 建構子 | 描述 |
| --- | --- |
| [Storage()](#Storage--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | 將值放入儲存中。 |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | 從儲存中取得資料。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 判斷儲存是否包含具有指定鍵的元素。 |

### Storage() {#Storage--}
```
public Storage()
```

### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

將值放入儲存中。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 值的鍵。 |
| value | TValue | 值。 |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

從儲存中取得資料。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 值的鍵。 |

**回傳值:**
TValue - 若資料集合中存在則回傳資料值，否則回傳 null。

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

判斷儲存是否包含具有指定鍵的元素。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 值的鍵。 |

**回傳值:**
boolean - 若儲存包含具有指定鍵的元素則返回 true，否則返回 false。