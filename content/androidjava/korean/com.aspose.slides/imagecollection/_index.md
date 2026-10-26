---
title: ImageCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: PPImage 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imagecollection/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

PPImage 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 포함된 이미지 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 다른 프레젠테이션에서 이미지 복사본을 추가합니다. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | 프레젠테이션에 이미지를 추가합니다. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | 스트림에서 프레젠테이션으로 이미지를 추가합니다. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | 스트림에서 이미지를 생성하고 프레젠테이션에 추가합니다. |
| [addImage(byte[] buffer)](#addImage-byte---) | 지정된 버퍼에서 프레젠테이션으로 이미지를 추가합니다. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Svg 객체에서 프레젠테이션으로 이미지를 추가합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 Java 반복자를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### size() {#size--}
```
public final int size()
```


컬렉션에 포함된 이미지 수를 반환합니다. 읽기 전용  int .

**반환:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IPPImage](../../com.aspose.slides/ippimage).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


다른 프레젠테이션에서 이미지 복사본을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | 소스 이미지. |

**반환:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


프레젠테이션에 이미지를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 추가할 이미지.

--------------------

이 메서드는 WMF/EMF 메타파일을 프레젠테이션에 삽입하기 전에 래스터 PNG 이미지로 변환합니다.

**반환:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


스트림에서 프레젠테이션으로 이미지를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지를 추가할 스트림.

--------------------

이 메서드는 WMF/EMF 메타파일을 래스터 PNG 이미지로 변환하지 않고도 프레젠테이션에 추가할 수 있습니다.

**반환:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


스트림에서 이미지를 생성하고 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지 파일을 추가할 스트림. |
| loadingStreamBehavior | int | 스트림에 적용될 동작. |

**반환:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


지정된 버퍼에서 프레젠테이션으로 이미지를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | byte[] | 버퍼. |

**반환:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


Svg 객체에서 프레젠테이션으로 이미지를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg 이미지 객체 [ISvgImage](../../com.aspose.slides/isvgimage) |

**반환:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


전체 컬렉션에 대한 Java 반복자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - 전체 컬렉션에 대한 java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용  boolean .

**반환:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


동기화 루트를 반환합니다. 읽기 전용  Object .

**반환:**
java.lang.Object