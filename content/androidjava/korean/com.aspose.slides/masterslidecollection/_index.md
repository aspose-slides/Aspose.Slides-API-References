---
title: MasterSlideCollection
second_title: Java API를 통한 Aspose.Slides for Android 참조
description: 마스터 슬라이드 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/masterslidecollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)  
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

마스터 슬라이드 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소의 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 사용되지 않는 마스터 슬라이드를 제거합니다. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 지정된 마스터 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |

### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 int.

**반환:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [MasterSlide](../../com.aspose.slides/masterslide).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)

### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 컬렉션에서 제거할 마스터 슬라이드. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0 기반 인덱스. |

--------------------

PptxEditException이 발생하는 것을 방지하려면 마스터의 HasDependingSlides 속성을 사전에 확인하십시오.

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

사용되지 않는 마스터 슬라이드를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ignorePreserveField | boolean | 이 메서드가 [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) 속성이 true로 설정되어 있더라도 사용되지 않은 마스터를 제거해야 하는지 여부를 결정합니다. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

지정된 마스터 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. 연결된 레이아웃 슬라이드도 복사됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 복제할 슬라이드. |

**반환:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - 추가된 슬라이드.

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 연결된 레이아웃 슬라이드도 복사됩니다.

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // 소스 프레젠테이션 파일을 로드하기 위해 Presentation 클래스를 인스턴스화합니다
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // 슬라이드를 복제할 대상 프레젠테이션을 위해 Presentation 클래스를 인스턴스화합니다
>      Presentation destPres = new Presentation();
>      try {
>          // 소스 프레젠테이션의 슬라이드 컬렉션에서 ISlide를 인스턴스화합니다
>          // 마스터 슬라이드
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // 대상 프레젠테이션의 마스터 슬라이드를 가져옵니다
>          IMasterSlideCollection masters = destPres.getMasters();
>          // 소스 프레젠테이션에서 원하는 마스터 슬라이드를 복제하여
>          // 대상 프레젠테이션의 마스터 컬렉션에 추가합니다
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // 대상 프레젠테이션의 슬라이드 컬렉션
>          ISlideCollection slds = destPres.getSlides();
>          // 소스 슬라이드를 대상 슬라이드 컬렉션에 복제합니다.
>          slds.addClone(SourceSlide, iSlide, true);
>          // 대상 프레젠테이션을 디스크에 저장합니다
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 복제할 슬라이드. |

**반환:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - 삽입된 마스터 슬라이드.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열에서 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

전체 컬렉션에 대한 java 반복자를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - 전체 컬렉션에 대한 java.util.Iterator.