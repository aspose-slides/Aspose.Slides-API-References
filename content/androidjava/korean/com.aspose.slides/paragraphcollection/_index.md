---
title: ParagraphCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 단락 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/paragraphcollection/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**모든 구현 인터페이스:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

단락 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | 컬렉션 끝에 Paragraph를 추가합니다. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | 컬렉션 끝에 ParagraphCollection의 내용을 추가합니다. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | List에서 특정 항목의 인덱스를 결정합니다. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 지정된 인덱스에 Paragraph를 삽입합니다. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 지정된 인덱스에 ParagraphCollection의 내용을 삽입합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되는지 여부를 결정합니다. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 배열에 복사하며, 특정 배열 인덱스에서 시작합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [getSlide()](#getSlide--) | 단락 컬렉션의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 단락 컬렉션의 부모 프레젠테이션을 반환합니다. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 지정된 HTML 문자열의 텍스트를 컬렉션에 추가합니다. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 지정된 HTML 문자열의 텍스트를 컬렉션에 추가합니다. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 지정된 단락을 HTML로 변환하고 String 객체로 반환합니다. |

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용이면 true; 그렇지 않으면 false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

컬렉션 끝에 Paragraph를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 컬렉션 끝에 추가될 Paragraph. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

컬렉션 끝에 ParagraphCollection의 내용을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 컬렉션 끝에 추가될 ParagraphCollection. |

**반환값:**
int - Paragraph가 추가된 인덱스, 또는 추가할 것이 없을 경우 -1.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

List에서 특정 항목의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | List에서 찾을 객체. |

**반환값:**
int - 항목이 리스트에서 발견된 경우 그 인덱스; 그렇지 않으면 -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

지정된 인덱스에 Paragraph를 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | Paragraph가 삽입될 0부터 시작하는 인덱스. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 삽입할 Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

지정된 인덱스에 ParagraphCollection의 내용을 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | Paragraphs가 삽입될 0부터 시작하는 인덱스. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 삽입할 paragraphs. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 요소를 제거합니다.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되는지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 객체. |

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목이 발견되면 true; 그렇지 않으면 false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 배열에 복사하며, 특정 배열 인덱스에서 시작합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | 복사된 요소가 저장될 1차원 배열. [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 복사된 요소. 배열은 0부터 시작하는 인덱스를 가져야 합니다. |
| arrayIndex | int | 복사가 시작되는 배열의 0부터 시작하는 인덱스. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 제거할 객체. |

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목이 성공적으로 제거되면 true; 그렇지 않으면 false. 원래 [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목을 찾지 못한 경우에도 false를 반환합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator for the entire collection.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

단락 컬렉션의 부모 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환값:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

단락 컬렉션의 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

지정된 HTML 문자열의 텍스트를 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | HTML 텍스트. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

지정된 HTML 문자열의 텍스트를 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | HTML 텍스트. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI를 해결하고 참조된 객체를 가져오는 Resolver 콜백 객체. |
| uri | java.lang.String | HTML 문서를 추가하기 위한 URI. 상대 링크를 해결하는 데 사용됩니다. |

Resolver를 지정하면 잠재적인 취약점이 발생할 수 있습니다. 주의해서 사용하십시오.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

지정된 단락을 HTML로 변환하고 String 객체로 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| firstParagraphIndex | int | 첫 번째 단락 인덱스 int |
| paragraphsCount | int | 단락 개수 int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | 변환 옵션 [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**반환값:**
java.lang.String - 생성된 HTML.