---
title: ImageTransformOCollectionEffectiveData
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 효과적인 이미지 변환 효과의 읽기 전용 컬렉션을 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)  
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

읽기 전용 이미지 변환 효과 컬렉션을 나타내는 불변 객체입니다.

--------------------

Name IImageTransformOperationCollectionEffectiveData truncuted to IImageTransformOCollectionEffectiveData because of COM names length cannot be more then 39.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 포함된 이미지 효과의 개수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 요소를 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 현재 객체와 같은지 판단합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공하며, 해시 테이블과 같은 해시 알고리즘 및 데이터 구조에 사용할 수 있습니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator 를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)인지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |

### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```

### size() {#size--}
```
public final int size()
```

컬렉션에 포함된 이미지 효과의 개수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```

인덱스로 요소를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환:**  
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) 객체.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 객체가 현재 객체와 같은지 판단합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 객체와 비교할 객체. |

**반환:**  
boolean - 지정된 객체가 현재 객체와 같으면 true; 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공하며, 해시 테이블과 같은 해시 알고리즘 및 데이터 구조에 사용할 수 있습니다.

**반환:**  
int - 현재 객체의 해시 코드.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - 컬렉션을 순회하는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```

전체 컬렉션에 대한 java iterator 를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - 전체 컬렉션에 대한 java.util.Iterator.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 채울 배열. |
| index | int | 대상 배열에서 시작 위치. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)인지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환:**  
java.lang.Object