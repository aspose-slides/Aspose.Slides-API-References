---
title: IMasterSlideCollection
second_title: Aspose.Slides for Java API 참조
description: 마스터 슬라이드 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imasterslidecollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

마스터 슬라이드의 컬렉션을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 사용되지 않는 마스터 슬라이드를 제거합니다. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 지정된 마스터 슬라이드의 복사본을 컬렉션 끝에 추가합니다. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 컬렉션에서 제거할 마스터 슬라이드입니다. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 요소를 제거합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 제거할 요소의 0 기반 인덱스입니다. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

사용되지 않는 마스터 슬라이드를 제거합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | 해당 마스터의 [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) 속성이 true 로 설정되어 있더라도 사용되지 않은 마스터를 제거해야 하는지 결정합니다. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

지정된 마스터 슬라이드의 복사본을 컬렉션 끝에 추가합니다. 연결된 레이아웃 슬라이드도 복사됩니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 복제할 슬라이드입니다. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 추가된 슬라이드.

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 연결된 레이아웃 슬라이드도 복사됩니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 복제할 슬라이드입니다. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 삽입된 마스터 슬라이드.