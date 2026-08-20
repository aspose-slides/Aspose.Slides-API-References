---
title: Storage
second_title: Aspose.Slides Java API 레퍼런스
description: 임시 데이터 저장소를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/storage/
---
**Inheritance:**
java.lang.Object
```
public final class Storage
```

[WebDocument](../../com.aspose.slides/webdocument)에 대한 임시 데이터 저장소를 나타냅니다.
## Constructors

| Constructor | Description |
| --- | --- |
| [Storage()](#Storage--) |  |
## Methods

| Method | Description |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | 값을 저장소에 저장합니다. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | 저장소에서 데이터를 가져옵니다. |
| [containsKey(String key)](#containsKey-java.lang.String-) | 저장소에 지정된 키를 가진 요소가 포함되어 있는지 확인합니다. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


값을 저장소에 저장합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | 값의 키. |
| value | TValue | 값. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


저장소에서 데이터를 가져옵니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | 값의 키. |

**Returns:**
TValue - 데이터 컬렉션에 존재하는 경우 데이터 값이며, 없으면 null입니다.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


저장소에 지정된 키를 가진 요소가 포함되어 있는지 확인합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | 값의 키. |

**Returns:**
boolean - 저장소에 지정된 키를 가진 요소가 포함되어 있으면 true, 그렇지 않으면 false.