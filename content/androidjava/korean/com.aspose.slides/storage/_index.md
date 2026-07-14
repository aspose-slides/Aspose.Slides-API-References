---
title: Storage
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 임시 데이터 저장소를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/storage/
---
**상속:**  
java.lang.Object  
```
public final class Storage
```

[WebDocument](../../com.aspose.slides/webdocument)에 대한 임시 데이터 저장소를 나타냅니다.

## 생성자

| Constructor | Description |
| --- | --- |
| [Storage()](#Storage--) |  |

## 메서드

| Method | Description |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | 값을 저장소에 넣습니다. |
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

값을 저장소에 넣습니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | 값의 키. |
| value | TValue | 값. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

저장소에서 데이터를 가져옵니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | 값의 키. |

**반환값:**
TValue - 데이터 컬렉션에 존재하면 데이터 값, 그렇지 않으면 null.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

저장소에 지정된 키를 가진 요소가 포함되어 있는지 확인합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | 값의 키. |

**반환값:**
boolean - 저장소에 지정된 키를 가진 요소가 포함되어 있으면 true, 그렇지 않으면 false.