---
title: IParagraphCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 단락 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iparagraphcollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

문단 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | 컬렉션 끝에 Paragraph를 추가합니다. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | 컬렉션 끝에 ParagraphCollection의 내용을 추가합니다. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 지정된 인덱스에 Paragraph를 컬렉션에 삽입합니다. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 지정된 인덱스에 ParagraphCollection의 내용을 컬렉션에 삽입합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | 특정 단락의 첫 번째 발생을 제거합니다. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 지정된 html 문자열에서 텍스트를 컬렉션에 추가합니다. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 지정된 html 문자열에서 텍스트를 컬렉션에 추가합니다. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 지정된 단락을 HTML로 변환하고 String 객체로 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

컬렉션 끝에 Paragraph를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 컬렉션 끝에 추가될 Paragraph입니다. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

컬렉션 끝에 ParagraphCollection의 내용을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 컬렉션 끝에 추가될 ParagraphCollection입니다. |

**반환값:**
int - Paragraph가 추가된 인덱스 또는 추가할 것이 없으면 -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

지정된 인덱스에 Paragraph를 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | Paragraph를 삽입할 0 기반 인덱스. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 삽입할 Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

지정된 인덱스에 ParagraphCollection의 내용을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 단락을 삽입할 0 기반 인덱스. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 삽입할 단락들. |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0 기반 인덱스. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

특정 단락의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 컬렉션에서 제거할 단락. |

**반환값:**
boolean - 항목이 성공적으로 제거되면 true; 그렇지 않으면 false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

지정된 html 문자열에서 텍스트를 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | HTML 텍스트. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

지정된 html 문자열에서 텍스트를 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | HTML 텍스트. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI를 해결하고 참조된 객체를 가져오는 Resolver 콜백 객체. |
| uri | java.lang.String | HTML 문서를 추가하기 위한 URI. 상대 링크를 해결하는 데 사용됩니다.

--------------------

Resolver를 지정하면 잠재적인 취약점이 발생할 수 있습니다. 주의해서 사용하십시오.
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

지정된 단락을 HTML로 변환하고 String 객체로 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstParagraphIndex | int | 첫 번째 단락 인덱스 int |
| paragraphsCount | int | 단락 개수 int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | 변환 옵션 [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**반환값:**
java.lang.String - 생성된 HTML.