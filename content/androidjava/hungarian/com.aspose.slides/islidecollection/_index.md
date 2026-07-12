---
title: ISlideCollection
second_title: Aspose.Slides Androidhoz a Java API hivatkozáson keresztül
description: Diák egy gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/islidecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Diákat tartalmazó gyűjteményt reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elemet a megadott indexen. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | A megadott dia egy példányát hozzáadja a gyűjtemény végéhez. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | A megadott dia egy példányát hozzáadja a megadott szakasz végéhez. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába illeszti. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Új üres diát ad a gyűjtemény végéhez. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába illeszti. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | A megadott dia egy példányát hozzáadja a gyűjtemény végéhez. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába illeszti. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | A megadott forrásdia egy példányát hozzáadja a gyűjtemény végéhez. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | A megadott forrásdia egy példányát a gyűjtemény megadott pozíciójába illeszti. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Eltávolítja a meghatározott objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexű elemet. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt, amely tartalmazza az összes diát. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes diát tartalmazza. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | A diák áthelyezése a gyűjteményből a megadott pozícióba. A diák az indextől kezdve a listában szereplésük sorrendjében kerülnek elhelyezésre. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Visszaadja a megadott dia indexét a gyűjteményben. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Diákat hoz létre a PDF-dokumentumból, és hozzáadja a gyűjtemény végéhez. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Diákat hoz létre a PDF-dokumentumból, és a pdf importálási beállításokat figyelembe véve hozzáadja a gyűjtemény végéhez. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Diákat hoz létre a PDF-dokumentumból, és hozzáadja a gyűjtemény végéhez. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Diákat hoz létre a PDF-dokumentumból, és hozzáadja a gyűjtemény végéhez. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Diákat hoz létre HTML szövegből, és hozzáadja a gyűjtemény végéhez. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Diákat hoz létre HTML szövegből, és hozzáadja a gyűjtemény végéhez. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Diákat hoz létre HTML szövegből, és hozzáadja a gyűjtemény végéhez. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Diákat hoz létre HTML szövegből, és hozzáadja a gyűjtemény végéhez. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Visszaadja az elemet a megadott indexen. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

A megadott dia egy példányát hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |

--------------------

Amikor diát klónozunk különböző prezentációk között, a dia mesteroldala is klónozható. Egy belső nyilvántartás használatos az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozza ugyanazon mesterdia több klónjának létrehozását. A mesterdiák manuális klónozása sem akadályozott, sem nyilvántartott. Ha nagyobb irányítást igényel a klónozási folyamat felett, használja a \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) vagy a \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) metódusokat diákok klónozásához, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) vagy [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) a layoukok klónozásához és [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) a mesterek klónozásához.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

A megadott dia egy példányát hozzáadja a megadott szakasz végéhez.

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
>      // Most a második szekció tartalmaz egy példányt az első diából.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| section | [ISection](../../com.aspose.slides/isection) | Új dia szekciója. |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

A megadott dia egy példányát a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |

--------------------

Amikor diát klónozunk különböző prezentációk között, a dia mesteroldala is klónozható. Egy belső nyilvántartás használatos az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozza ugyanazon mesterdia több klónjának létrehozását. A mesterdiák manuális klónozása sem akadályozott, sem nyilvántartott. Ha nagyobb irányítást igényel a klónozási folyamat felett, használja a \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) vagy a \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) metódusokat diákok klónozásához és [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) a mesterek klónozásához.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Új üres diát ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia elrendezése. |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Hozzáadott dia.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

A megadott dia egy példányát a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia elrendezése. |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

A megadott dia egy példányát hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Az új dia elrendezése. |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

A megadott dia egy példányát a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Az új dia elrendezése. |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

A megadott forrásdia egy példányát hozzáadja a gyűjtemény végéhez. A megfelelő elrendezés automatikusan a megadott mesterből lesz kiválasztva (a megfelelő elrendezés az a elrendezés, amelynek típusa vagy neve megegyezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), ellenkező esetben PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Új dia mesteroldala. |
| allowCloneMissingLayout | boolean | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), ellenkező esetben PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis). |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

A megadott forrásdia egy példányát a gyűjtemény megadott pozíciójába illeszti. A megfelelő elrendezés automatikusan a megadott mesterből lesz kiválasztva (a megfelelő elrendezés az a elrendezés, amelynek típusa vagy neve megegyezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), ellenkező esetben PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Új dia mesteroldala. |
| allowCloneMissingLayout | boolean | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), ellenkező esetben PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis). |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Eltávolítja a meghatározott objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | A gyűjteményből eltávolítandó dia. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a gyűjteményben a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó elem nullárol kezdődő indexe. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Tömb, amely [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes diát tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első hozzáadandó dia indexe. |
| count | int | A hozzáadandó diák száma. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Tömb, amely [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Áthelyezi a diát a gyűjteményből a megadott pozícióba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Cél index. |
| slide | [ISlide](../../com.aspose.slides/islide) | Áthelyezendő dia. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Áthelyezi a diákat a gyűjteményből a megadott pozícióba. A diák az indextől kezdve a listában megjelenésük sorrendjében kerülnek elhelyezésre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Cél index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Áthelyezendő diák. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Visszaadja a megadott dia indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Keresendő dia. |

**Visszatérési érték:**
int - A dia indexe vagy -1, ha a dia nem ebbe a gyűjteménybe tartozik.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Diákat hoz létre a PDF-dokumentumból, és hozzáadja a gyűjtemény végéhez.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | A PDF-dokumentum elérési útvonala. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Diákat hoz létre a PDF-dokumentumból, és a pdf importálási beállításokat figyelembe véve hozzáadja a gyűjtemény végéhez.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | A PDF-dokumentum elérési útvonala. |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF importálás beállításai. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Diákat hoz létre a PDF-dokumentumból, és hozzáadja a gyűjtemény végéhez.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pdfStream | java.io.InputStream | A PDF-dokumentum forrásaként használandó adatfolyam. |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF importálás beállításai. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Diákat hoz létre a PDF-dokumentumból, és hozzáadja a gyűjtemény végéhez.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pdfStream | java.io.InputStream | A PDF-dokumentum forrásaként használandó adatfolyam. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Diákat hoz létre HTML szövegből, és hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | java.lang.String | A hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Diákat hoz létre HTML szövegből, és hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | java.lang.String | A hozzáadandó HTML. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Diákat hoz létre HTML szövegből, és hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Egy adatfolyam, amely a HTML fájl forrásaként szolgál. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Diákat hoz létre HTML szövegből, és hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Egy adatfolyam, amely a HTML fájl forrásaként szolgál. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Diákat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlText | java.lang.String | A hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Diákat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlText | java.lang.String | A hozzáadandó HTML. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Diákat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlStream | java.io.InputStream | Egy adatfolyam, amely a HTML fájl forrásaként szolgál. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Diákat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlStream | java.io.InputStream | Egy adatfolyam, amely a HTML fájl forrásaként szolgál. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Diákat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlText | java.lang.String | A hozzáadandó HTML. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: egy új diával vagy a megadott indexű diával. Ha **true**, akkor az adatbeszúrás a megadott indexű dia üres helyéről kezdődik. Ha **false**, akkor az adatok a létrehozott diákra kerülnek. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Diákat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlText | java.lang.String | A hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: egy új diával vagy a megadott indexű diával. Ha **true**, akkor az adatbeszúrás a megadott indexű dia üres helyéről kezdődik. Ha **false**, akkor az adatok a létrehozott diákra kerülnek. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Diákat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlStream | java.io.InputStream | Egy adatfolyam, amely a HTML fájl forrásaként szolgál. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: egy új diával vagy a megadott indexű diával. Ha **true**, akkor az adatbeszúrás a megadott indexű dia üres helyéről kezdődik. Ha **false**, akkor az adatok a létrehozott diákra kerülnek. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Diákat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlStream | java.io.InputStream | Egy adatfolyam, amely a HTML fájl forrásaként szolgál. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: egy új diával vagy a megadott indexű diával. Ha **true**, akkor az adatbeszúrás a megadott indexű dia üres helyéről kezdődik. Ha **false**, akkor az adatok a létrehozott diákra kerülnek. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.