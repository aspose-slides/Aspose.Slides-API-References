---
title: ICaptionsCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 닫힌 자막의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icaptionscollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

닫힌 자막의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 닫힌 자막을 반환합니다. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | 컬렉션 끝에 WebVTT 닫힌 자막을 추가합니다. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | 스트림에서 컬렉션 끝에 WebVTT 닫힌 자막을 추가합니다. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | 컬렉션에서 지정된 닫힌 자막을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 닫힌 자막을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 닫힌 자막을 제거합니다. |
| [getCount()](#getCount--) | 컬렉션의 요소 수를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

지정된 인덱스에 있는 닫힌 자막을 반환합니다. 읽기 전용 [ICaptions](../../com.aspose.slides/icaptions).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

컬렉션 끝에 WebVTT 닫힌 자막을 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| label | java.lang.String | 닫힌 자막의 라벨. |
| filePath | java.lang.String | WebVTT 파일 경로. |

**반환:**
[ICaptions](../../com.aspose.slides/icaptions) - 추가된 [ICaptions](../../com.aspose.slides/icaptions) 인스턴스.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

스트림에서 컬렉션 끝에 WebVTT 닫힌 자막을 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| label | java.lang.String | 닫힌 자막의 라벨. |
| stream | java.io.InputStream | WebVTT 형식의 데이터를 포함하는 입력 스트림. |

**반환:**
[ICaptions](../../com.aspose.slides/icaptions) - 추가된 [ICaptions](../../com.aspose.slides/icaptions) 인스턴스.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

컬렉션에서 지정된 닫힌 자막을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 제거할 닫힌 자막. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스에 있는 닫힌 자막을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 제거할 닫힌 자막의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 닫힌 자막을 제거합니다.

### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션의 요소 수를 반환합니다. 읽기 전용 int .

**반환:**
int