---
title: IMasterSlideCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 마스터 슬라이드 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imasterslidecollection/
---
**모든 구현된 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

마스터 슬라이드 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 사용되지 않는 마스터 슬라이드를 제거합니다. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 지정된 마스터 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [IMasterSlide](../../com.aspose.slides/imasterslide).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 컬렉션에서 제거할 마스터 슬라이드. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


컬렉션에서 지정된 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


사용되지 않는 마스터 슬라이드를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ignorePreserveField | boolean | 이 메서드가 [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) 속성이 true로 설정되어 있더라도 사용되지 않은 마스터를 제거해야 하는지 여부를 결정합니다. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


지정된 마스터 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. 연결된 레이아웃 슬라이드도 복사됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 복제할 슬라이드. |

**반환값:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 추가된 슬라이드.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 연결된 레이아웃 슬라이드도 복사됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 복제할 슬라이드. |

**반환값:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 삽입된 마스터 슬라이드.