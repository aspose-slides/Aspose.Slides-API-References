---
title: ISlideCollection
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 슬라이드의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/islidecollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

슬라이드 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 지정된 슬라이드의 복사본을 컬렉션 끝에 추가합니다. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 지정된 슬라이드의 복사본을 지정된 섹션의 끝에 추가합니다. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 새 빈 슬라이드를 컬렉션 끝에 추가합니다. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 지정된 슬라이드의 복사본을 컬렉션 끝에 추가합니다. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 지정된 원본 슬라이드의 복사본을 컬렉션 끝에 추가합니다. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 지정된 원본 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [toArray()](#toArray--) | 모든 슬라이드가 포함된 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 지정된 범위의 모든 슬라이드가 포함된 배열을 생성하고 반환합니다. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 컬렉션에서 지정된 슬라이드의 인덱스를 반환합니다. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF 문서에서 슬라이드를 생성하고 PDF 가져오기 옵션을 고려하여 컬렉션 끝에 추가합니다. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [ISlide](../../com.aspose.slides/islide).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

지정된 슬라이드의 복사본을 컬렉션 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |

---

다른 프레젠테이션 간에 슬라이드를 복제할 때 슬라이드의 마스터도 복제될 수 있습니다. 내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되거나 등록되지 않습니다. 복제 프로세스를 보다 세밀하게 제어하려면 \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) 또는 \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) 를 사용하여 슬라이드를 복제하고, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 또는 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 로 레이아웃을 복제하고, [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 로 마스터를 복제하십시오.

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 새 슬라이드.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

지정된 슬라이드의 복사본을 지정된 섹션의 끝에 추가합니다.

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
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| section | [ISection](../../com.aspose.slides/isection) | 새 슬라이드의 섹션. |

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 새 슬라이드.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |

---

다른 프레젠테이션 간에 슬라이드를 복제할 때 슬라이드의 마스터도 복제될 수 있습니다. 내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되거나 등록되지 않습니다. 복제 프로세스를 보다 세밀하게 제어하려면 \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) 또는 \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) 를 사용하여 슬라이드를 복제하고 [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 로 마스터를 복제하십시오.

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 삽입된 슬라이드.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

새 빈 슬라이드를 컬렉션 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 슬라이드 레이아웃. |

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 추가된 슬라이드.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 슬라이드 레이아웃. |

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 삽입된 슬라이드.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

지정된 슬라이드의 복사본을 컬렉션 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 새 슬라이드의 레이아웃 슬라이드. |

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 새 슬라이드.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 새 슬라이드의 레이아웃 슬라이드. |

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 삽입된 슬라이드.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

지정된 원본 슬라이드의 복사본을 컬렉션 끝에 추가합니다. 적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다). 적절한 레이아웃이 없을 경우, 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 새 슬라이드의 마스터 슬라이드. |
| allowCloneMissingLayout | boolean | 지정된 마스터에 적절한 레이아웃이 없으면 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 새 슬라이드.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

지정된 원본 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다). 적절한 레이아웃이 없을 경우, 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 복제할 슬라이드. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 새 슬라이드의 마스터 슬라이드. |
| allowCloneMissingLayout | boolean | 지정된 마스터에 적절한 레이아웃이 없으면 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |

**반환값:**
[ISlide](../../com.aspose.slides/islide) - 삽입된 슬라이드.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | 컬렉션에서 제거할 슬라이드. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 요소를 제거합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

모든 슬라이드가 포함된 배열을 생성하고 반환합니다.

**반환값:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 배열

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

지정된 범위의 모든 슬라이드가 포함된 배열을 생성하고 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | 추가할 첫 번째 슬라이드의 인덱스. |
| count | int | 추가할 슬라이드 수. |

**반환값:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 배열

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

컬렉션에서 슬라이드를 지정된 위치로 이동합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 대상 인덱스. |
| slide | [ISlide](../../com.aspose.slides/islide) | 이동할 슬라이드. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

컬렉션에서 슬라이드를 지정된 위치로 이동합니다. 슬라이드는 인덱스부터 리스트에 나타나는 순서대로 배치됩니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 대상 인덱스. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 이동할 슬라이드. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

컬렉션에서 지정된 슬라이드의 인덱스를 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 찾을 슬라이드. |

**반환값:**
int - 슬라이드의 인덱스 또는 슬라이드가 이 컬렉션에 속하지 않으면 -1.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

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
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | PDF 문서에 대한 경로 |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF 문서에서 슬라이드를 생성하고 PDF 가져오기 옵션을 고려하여 컬렉션 끝에 추가합니다.

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
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | PDF 문서에 대한 경로 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 가져오기 옵션 |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF 문서의 소스로 사용할 스트림 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 가져오기 옵션 |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF 문서의 소스로 사용할 스트림 |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | 추가할 HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오기 위해 사용되는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | 추가할 HTML. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림 객체. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오기 위해 사용되는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림 객체. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlText | java.lang.String | 추가할 HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오기 위해 사용되는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlText | java.lang.String | 추가할 HTML. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림 객체. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오기 위해 사용되는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림 객체. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlText | java.lang.String | 추가할 HTML. |
| useSlideWithIndexAsStart | boolean | 이 플래그는 삽입을 시작하는 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**인 경우, 지정된 인덱스의 슬라이드에서 빈 공간부터 데이터 삽입이 시작됩니다. **false**인 경우, 생성된 슬라이드에 데이터가 추가됩니다. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlText | java.lang.String | 추가할 HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오기 위해 사용되는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |
| useSlideWithIndexAsStart | boolean | 이 플래그는 삽입을 시작하는 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**인 경우, 지정된 인덱스의 슬라이드에서 빈 공간부터 데이터 삽입이 시작됩니다. **false**인 경우, 생성된 슬라이드에 데이터가 추가됩니다. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림 객체. |
| useSlideWithIndexAsStart | boolean | 이 플래그는 삽입을 시작하는 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**인 경우, 지정된 인덱스의 슬라이드에서 빈 공간부터 데이터 삽입이 시작됩니다. **false**인 경우, 생성된 슬라이드에 데이터가 추가됩니다. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삽입 위치. |
| htmlStream | java.io.InputStream | HTML 파일의 소스로 사용할 스트림 객체. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오기 위해 사용되는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | java.lang.String | 지정된 HTML의 URI. 상대 링크를 해결하는 데 사용됩니다. |
| useSlideWithIndexAsStart | boolean | 이 플래그는 삽입을 시작하는 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**인 경우, 지정된 인덱스의 슬라이드에서 빈 공간부터 데이터 삽입이 시작됩니다. **false**인 경우, 생성된 슬라이드에 데이터가 추가됩니다. |

**반환값:**
com.aspose.slides.ISlide[] - 추가된 슬라이드.