---
title: ISlideCollection
second_title: Aspose.Slides Java API referencia
description: Egy diákgyűjteményt képvisel.
type: docs
url: /hu/com.aspose.slides/islidecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

A diák gyűjteményét képviseli.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Az adott indexen lévő elemet adja vissza. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | A megadott dia másolatát a gyűjtemény végéhez adja hozzá. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | A megadott dia másolatát a megadott szekció végéhez adja hozzá. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | A megadott dia másolatát a gyűjtemény megadott pozíciójába illeszti. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Új üres diát ad a gyűjtemény végéhez. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | A megadott dia másolatát a gyűjtemény megadott pozíciójába illeszti. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | A megadott dia másolatát a gyűjtemény végéhez adja hozzá. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | A megadott dia másolatát a gyűjtemény megadott pozíciójába illeszti. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | A megadott forrásdia másolatát a gyűjtemény végéhez adja hozzá. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | A megadott forrásdia másolatát a gyűjtemény megadott pozíciójába illeszti. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Eltávolítja a specifikus objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes diát tartalmazza. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Áthelyezi a diák a gyűjteményből a megadott pozícióba. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Visszaadja a megadott dia indexét a gyűjteményben. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Létrehozza a diákat a PDF-dokumentumból, és a gyűjtemény végéhez adja őket. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Létrehozza a diákat a PDF-dokumentumból, és a PDF importálási beállításokat figyelembe véve a gyűjtemény végéhez adja őket. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Létrehozza a diákat a PDF-dokumentumból, és a gyűjtemény végéhez adja őket. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Létrehozza a diákat a PDF-dokumentumból, és a gyűjtemény végéhez adja őket. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Létrehozza a diákat HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Létrehozza a diákat HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Létrehozza a diákat HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Létrehozza a diákat HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Létrehozza a diákat HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Az adott indexen lévő elemet adja vissza. Csak olvasható [ISlide](../../com.aspose.slides/islide).

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

A megadott dia másolatát a gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |

--------------------

Amikor egy diát különböző bemutatók között klónozunk, a dia mesterét is lehet klónozni. Belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több klónjának létrehozását. A mesterdia kézi klónozása nem lesz sem megakadályozva, sem regisztrálva. Ha nagyobb szabályozásra van szükség a klónozási folyamat során, használja a \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) vagy a \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) a diákklónozáshoz, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) vagy [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) a layoukok klónozásához és [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) a mesterek klónozásához.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

A megadott dia másolatát a megadott szekció végéhez adja hozzá.

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
>      // Most a második szakasz tartalmaz egy másolatot az első diáról.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| section | [ISection](../../com.aspose.slides/isection) | Szekció az új diának. |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

A megadott dia másolatát a megadott pozícióba illeszti a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |

--------------------

Amikor egy diát különböző bemutatók között klónozunk, a dia mesterét is lehet klónozni. Belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több klónjának létrehozását. A mesterdia kézi klónozása nem lesz sem megakadályozva, sem regisztrálva. Ha nagyobb szabályozásra van szükség a klónozási folyamat során, használja a \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) vagy a \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) a diákklónozáshoz és [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) a mesterek klónozásához.

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

A megadott dia másolatát a megadott pozícióba illeszti a gyűjteménybe.

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

A megadott dia másolatát a gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Új dia elrendezése. |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

A megadott dia másolatát a megadott pozícióba illeszti a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Új dia elrendezése. |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

A megadott forrás dia másolatát a gyűjtemény végéhez adja hozzá. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott mastertől (a megfelelő elrendezés az, amelynek típusa vagy neve megegyezik a forrás dia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrás dia elrendezése klónozásra kerül (ha allowCloneMissingLayout igaz), vagy PptxEditException dobódik (ha allowCloneMissingLayout hamis).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Mesterdia az új diához. |
| allowCloneMissingLayout | boolean | Ha nincs megfelelő elrendezés a megadott mesterben, akkor a forrás dia elrendezése klónozásra kerül (ha allowCloneMissingLayout igaz), vagy PptxEditException dobódik (ha allowCloneMissingLayout hamis). |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

A megadott forrás dia másolatát a megadott pozícióba illeszti a gyűjteménybe. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott mastertől (a megfelelő elrendezés az, amelynek típusa vagy neve megegyezik a forrás dia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrás dia elrendezése klónozásra kerül (ha allowCloneMissingLayout igaz), vagy PptxEditException dobódik (ha allowCloneMissingLayout hamis).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Mesterdia az új diához. |
| allowCloneMissingLayout | boolean | Ha nincs megfelelő elrendezés a megadott mesterben, akkor a forrás dia elrendezése klónozásra kerül (ha allowCloneMissingLayout igaz), vagy PptxEditException dobódik (ha allowCloneMissingLayout hamis). |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Eltávolítja a specifikus objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Az eltávolítandó dia a gyűjteményből. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a gyűjtemény megadott indexű elemét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A 0-bázisú index az eltávolítandó elemhez. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) tömbje

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
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) tömbje

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

Áthelyezi a diákat a gyűjteményből a megadott pozícióba. A diák az indexnél kezdődően a listában megjelenő sorrendben lesznek elhelyezve.

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
int - Dia indexe vagy -1, ha a dia nem ebből a gyűjteményből származik.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Létrehozza a diákat a PDF-dokumentumból, és a gyűjtemény végéhez adja őket.

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
| path | java.lang.String | Az útvonal a PDF dokumentumhoz |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```


Diákat hoz létre a PDF dokumentumból, és a gyűjtemény végéhez adja őket a pdf importálási beállítások figyelembevételével.

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
| path | java.lang.String | Az útvonal a PDF dokumentumhoz |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | pdf importálási beállítások |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```


Diákat hoz létre a PDF dokumentumból, és a gyűjtemény végéhez adja őket.

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
| pdfStream | java.io.InputStream | Egy adatfolyam, amely a PDF dokumentum forrásaként lesz használva |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | pdf importálási beállítások |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```


Diákat hoz létre a PDF dokumentumból, és a gyűjtemény végéhez adja őket.

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
| pdfStream | java.io.InputStream | Egy adatfolyam, amely a PDF dokumentum forrásaként lesz használva |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```


Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | java.lang.String | A hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```


Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

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


Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Egy Stream objektum, amely a HTML fájl forrásaként lesz használva. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```


Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Egy Stream objektum, amely a HTML fájl forrásaként lesz használva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```


Diákat hoz létre HTML szövegből, és a megadott pozícióba szúrja be őket a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlText | java.lang.String | A hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```


Diákat hoz létre HTML szövegből, és a megadott pozícióba szúrja be őket a gyűjteményben.

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


Diákat hoz létre HTML szövegből, és a megadott pozícióba szúrja be őket a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlStream | java.io.InputStream | Egy Stream objektum, amely a HTML fájl forrásaként lesz használva. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```


Diákat hoz létre HTML szövegből, és a megadott pozícióba szúrja be őket a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlStream | java.io.InputStream | Egy Stream objektum, amely a HTML fájl forrásaként lesz használva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```


Diákat hoz létre HTML szövegből, és a megadott pozícióba szúrja be őket a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlText | java.lang.String | A hozzáadandó HTML. |
| useSlideWithIndexAsStart | boolean | Ez a jelző meghatározza, hogyan kezdődjön a beszúrás: egy új diától vagy a megadott indexű diától. Ha **true**, az adatok beszúrása az adott indexű dia üres területéről kezdődik. Ha **false**, az adatok a létrehozott diákhoz lesznek hozzáadva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


Diákat hoz létre HTML szövegből, és a megadott pozícióba szúrja be őket a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlText | java.lang.String | A hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |
| useSlideWithIndexAsStart | boolean | Ez a jelző meghatározza, hogyan kezdődjön a beszúrás: egy új diától vagy a megadott indexű diától. Ha **true**, az adatok beszúrása az adott indexű dia üres területéről kezdődik. Ha **false**, az adatok a létrehozott diákhoz lesznek hozzáadva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```


Diákat hoz létre HTML szövegből, és a megadott pozícióba szúrja be őket a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlStream | java.io.InputStream | Egy Stream objektum, amely a HTML fájl forrásaként lesz használva. |
| useSlideWithIndexAsStart | boolean | Ez a jelző meghatározza, hogyan kezdődjön a beszúrás: egy új diától vagy a megadott indexű diától. Ha **true**, az adatok beszúrása az adott indexű dia üres területéről kezdődik. Ha **false**, az adatok a létrehozott diákhoz lesznek hozzáadva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


Diákat hoz létre HTML szövegből, és a megadott pozícióba szúrja be őket a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrási pozíció. |
| htmlStream | java.io.InputStream | Egy Stream objektum, amely a HTML fájl forrásaként lesz használva. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |
| useSlideWithIndexAsStart | boolean | Ez a jelző meghatározza, hogyan kezdődjön a beszúrás: egy új diától vagy a megadott indexű diától. Ha **true**, az adatok beszúrása az adott indexű dia üres területéről kezdődik. Ha **false**, az adatok a létrehozott diákhoz lesznek hozzáadva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.