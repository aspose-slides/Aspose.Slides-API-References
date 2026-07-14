---
title: SlideCollection
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 슬라이드 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/slidecollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)  
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

슬라이드 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 지정된 슬라이드의 복사본을 지정된 섹션의 끝에 추가합니다. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 지정된 슬라이드의 복사본을 컬렉션의 지정 위치에 삽입합니다. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 새 빈 슬라이드를 컬렉션의 끝에 추가합니다. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 지정된 슬라이드의 복사본을 컬렉션의 지정 위치에 삽입합니다. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 지정된 슬라이드의 복사본을 컬렉션의 지정 위치에 삽입합니다. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 지정된 원본 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 지정된 원본 슬라이드의 복사본을 컬렉션의 지정 위치에 삽입합니다. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [toArray()](#toArray--) | 모든 슬라이드를 포함하는 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 지정된 범위의 모든 슬라이드를 포함하는 배열을 생성하고 반환합니다. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. 슬라이드는 인덱스부터 리스트에 나타나는 순서대로 배치됩니다. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 컬렉션에서 지정된 슬라이드의 인덱스를 반환합니다. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF 문서에서 슬라이드를 생성하고 PDF 가져오기 옵션을 고려하여 컬렉션의 끝에 추가합니다. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |

### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [Slide](../../com.aspose.slides/slide).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**  
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |

--------------------

슬라이드를 다른 프레젠테이션 간에 복제할 때 슬라이드 마스터도 복제될 수 있습니다. 내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되지 않으며 레지스트리에 기록되지 않습니다. 복제 프로세스를 보다 세밀하게 제어해야 하는 경우 \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) 또는 \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) 를 사용하고, 레이아웃 복제는 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 혹은 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 를, 마스터 복제는 [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 를 사용하십시오.

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 새 슬라이드.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

지정된 슬라이드의 복사본을 지정된 섹션의 끝에 추가합니다.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // 이제 두 번째 섹션에 첫 번째 슬라이드의 복사본이 포함됩니다.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| section | [ISection](../../com.aspose.slides/isection) | 새 슬라이드가 들어갈 섹션. |

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 새 슬라이드.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

지정된 슬라이드의 복사본을 컬렉션의 지정 위치에 삽입합니다.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // 같은 프레젠테이션 내 슬라이드 컬렉션 끝에 원하는 슬라이드를 복제합니다
>      ISlideCollection slds = pres.getSlides();
>      // 같은 프레젠테이션 내 지정된 인덱스로 원하는 슬라이드를 복제합니다
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // 수정된 프레젠테이션을 디스크에 저장합니다
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // 소스 프레젠테이션 파일을 로드하기 위해 Presentation 클래스를 인스턴스화합니다
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // 슬라이드가 복제될 대상 PPTX를 위해 Presentation 클래스를 인스턴스화합니다
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // 대상 프레젠테이션을 디스크에 저장합니다
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |

--------------------

슬라이드를 다른 프레젠테이션 간에 복제할 때 슬라이드 마스터도 복제될 수 있습니다. 내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되지 않으며 레지스트리에 기록되지 않습니다. 복제 프로세스를 보다 세밀하게 제어해야 하는 경우 \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) 또는 \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) 를 사용하고 마스터 복제는 [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 를 사용하십시오.

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 삽입된 슬라이드.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

새 빈 슬라이드를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 슬라이드 레이아웃. |

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 추가된 슬라이드.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

지정된 슬라이드의 복사본을 컬렉션의 지정 위치에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 슬라이드 레이아웃. |

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 삽입된 슬라이드.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 새 슬라이드의 레이아웃 슬라이드. |

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 새 슬라이드.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

지정된 슬라이드의 복사본을 컬렉션의 지정 위치에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 새 슬라이드의 레이아웃 슬라이드. |

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 삽입된 슬라이드.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

지정된 원본 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. 지정된 마스터에서 자동으로 적절한 레이아웃이 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃). 적절한 레이아웃이 없으면 원본 슬라이드 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 새 슬라이드의 마스터 슬라이드. |
| allowCloneMissingLayout | boolean | 지정된 마스터에 적절한 레이아웃이 없을 경우 원본 슬라이드 레이아웃을 복제할지 여부를 지정합니다. true이면 복제하고, false이면 PptxEditException을 발생시킵니다. |

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 새 슬라이드.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

지정된 원본 슬라이드의 복사본을 컬렉션의 지정 위치에 삽입합니다. 지정된 마스터에서 자동으로 적절한 레이아웃이 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃). 적절한 레이아웃이 없으면 원본 슬라이드 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 새 슬라이드의 마스터 슬라이드. |
| allowCloneMissingLayout | boolean | 지정된 마스터에 적절한 레이아웃이 없을 경우 원본 슬라이드 레이아웃을 복제할지 여부를 지정합니다. true이면 복제하고, false이면 PptxEditException을 발생시킵니다. |

**반환:**  
[ISlide](../../com.aspose.slides/islide) - 삽입된 슬라이드.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | 컬렉션에서 제거할 슬라이드. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0 기반 인덱스. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 컬렉션을 순회할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 전체 컬렉션에 대한 java.util.Iterator.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

모든 슬라이드를 포함하는 배열을 생성하고 반환합니다.

**반환:**  
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) 배열

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

지정된 범위의 모든 슬라이드를 포함하는 배열을 생성하고 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startIndex | int | 첫 번째 슬라이드의 인덱스. |
| count | int | 추가할 슬라이드 수. |

**반환:**  
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) 배열

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

컬렉션에서 슬라이드를 지정된 위치로 이동합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 대상 인덱스. |
| slide | [ISlide](../../com.aspose.slides/islide) | 이동할 슬라이드. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

컬렉션에서 슬라이드를 지정된 위치로 이동합니다. 슬라이드는 인덱스부터 리스트에 나타나는 순서대로 배치됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 대상 인덱스. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 이동할 슬라이드. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

컬렉션에서 지정된 슬라이드의 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 찾을 슬라이드. |

**반환:**  
int - 슬라이드 인덱스 또는 컬렉션에 없으면 -1.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | PDF 문서 경로 |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF 문서에서 슬라이드를 생성하고 PDF 가져오기 옵션을 고려하여 컬렉션의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | PDF 문서 경로 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 가져오기 옵션 |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF 문서의 소스로 사용할 스트림 |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF 문서의 소스로 사용할 스트림 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 가져오기 옵션 |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| htmlText | java.lang.String | 추가할 HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체. null이면 모든 외부 객체를 무시합니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| htmlText | java.lang.String | 추가할 HTML. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체. null이면 모든 외부 객체를 무시합니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

--------------------

> ```
> // Presentation 클래스를 인스턴스화합니다.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // AddFromHtml 메서드를 호출하고 HTML 파일을 전달합니다.
>          pres.getSlides().addFromHtml(fos);
>          // Save 메서드를 사용하여 파일을 PowerPoint 문서로 저장합니다.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlText | java.lang.String | 추가할 HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체. null이면 모든 외부 객체를 무시합니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlText | java.lang.String | 추가할 HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체. null이면 모든 외부 객체를 무시합니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |
| useSlideWithIndexAsStart | boolean | 이 플래그는 삽입을 새 슬라이드에서 시작할지 지정된 인덱스의 슬라이드에서 시작할지 결정합니다. **true**이면 지정된 인덱스 슬라이드의 빈 공간에서 시작합니다. **false**이면 만든 슬라이드에 데이터를 추가합니다. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlText | java.lang.String | 추가할 HTML. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlText | java.lang.String | 추가할 HTML. |
| useSlideWithIndexAsStart | boolean | 이 플래그는 삽입을 새 슬라이드에서 시작할지 지정된 인덱스의 슬라이드에서 시작할지 결정합니다. **true**이면 지정된 인덱스 슬라이드의 빈 공간에서 시작합니다. **false**이면 만든 슬라이드에 데이터를 추가합니다. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체. null이면 모든 외부 객체를 무시합니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체. null이면 모든 외부 객체를 무시합니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |
| useSlideWithIndexAsStart | boolean | 이 플래그는 삽입을 새 슬라이드에서 시작할지 지정된 인덱스의 슬라이드에서 시작할지 결정합니다. **true**이면 지정된 인덱스 슬라이드의 빈 공간에서 시작합니다. **false**이면 만든 슬라이드에 데이터를 추가합니다. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림. |
| useSlideWithIndexAsStart | boolean | 이 플래그는 삽입을 새 슬라이드에서 시작할지 지정된 인덱스의 슬라이드에서 시작할지 결정합니다. **true**이면 지정된 인덱스 슬라이드의 빈 공간에서 시작합니다. **false**이면 만든 슬라이드에 데이터를 추가합니다. |

**반환:**  
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |

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