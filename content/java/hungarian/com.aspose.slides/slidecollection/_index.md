---
title: SlideCollection
second_title: Aspose.Slides Java API-referencia
description: Diákok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/slidecollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden implementált interfész:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Diák gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Lekéri a gyűjteményben ténylegesen lévő elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Hozzáad egy megadott dia másolatát a megadott szekció végéhez. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Új üres diát ad a gyűjtemény végéhez. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Hozzáad egy megadott forrásdia másolatát a gyűjtemény végéhez. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Beszúr egy megadott forrásdia másolatát a gyűjtemény megadott pozíciójába. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Eltávolítja a specifikus objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [toArray()](#toArray--) | Létrehozza és visszaadja a benne lévő összes dia tömbjét. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehozza és visszaadja a megadott tartományban lévő összes dia tömbjét. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Áthelyezi a diákot a gyűjteményből a megadott pozícióba. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Visszaad a megadott dia indexét a gyűjteményben. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Létrehoz diákat a PDF dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Létrehoz diákat a PDF dokumentumból, és a PDF importálási beállítások figyelembevételével hozzáadja őket a gyűjtemény végéhez. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Létrehoz diákat a PDF dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Létrehoz diákat a PDF dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehoz diákat HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Létrehoz diákat HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehoz diákat HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Létrehoz diákat HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehoz diákat HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Létrehoz diákat HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Létrehoz diákat HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Létrehoz diákat HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehoz diákat HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Létrehoz diákat HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Létrehoz diákat HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Létrehoz diákat HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Másolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökér elemet. |

### size() {#size--}
```
public final int size()
```

Lekéri a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

#### Visszatér:
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Lekéri a megadott indexű elemet. Csak olvasható [Slide](../../com.aspose.slides/slide).

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Hozzáad egy megadott dia másolatát a gyűjtemény végéhez.

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Másolandó dia.

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) or \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) for cloning slides, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) or [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) for cloning layouts and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Új dia.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Hozzáad egy megadott dia másolatát a megadott szekció végéhez.

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
>      // Most a második szekció tartalmaz egy másolatot az első diáról.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Másolandó dia. |
| section | [ISection](../../com.aspose.slides/isection) | Szekció az új diához. |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely egy bemutató fájlt képvisel
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // A kívánt diát a bemutatóban lévő diakollekció végére klónozza
>      ISlideCollection slds = pres.getSlides();
>      // A kívánt diát a megadott indexre klónozza a bemutatóban
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // A módosított bemutatót lemezre írja
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Példányosítja a Presentation osztályt a forrás bemutató fájl betöltéséhez
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Példányosítja a Presentation osztályt a cél PPTX-hez (ahová a dia klónozva lesz)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // A cél bemutatót lemezre írja
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Másolandó dia.

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) or \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Hozzáad egy új üres diát a gyűjtemény végéhez.

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Elrendezés a diához. |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Hozzáadott dia.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába.

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Új dia indexe. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Elrendezés a diához. |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Hozzáad egy megadott dia másolatát a gyűjtemény végéhez.

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Másolandó dia. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Új dia elrendezése. |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába.

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Másolandó dia. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Új dia elrendezése. |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Hozzáad egy megadott forrásdia másolatát a gyűjtemény végéhez. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott masterből (a megfelelő elrendezés a forrásdia elrendezésével azonos Type vagy Name értékkel rendelkező elrendezés). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout true), vagy PptxEditException kerül dobásra (ha false).

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Másolandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Új dia mastere. |
| allowCloneMissingLayout | boolean | Ha a megadott masterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha true), vagy PptxEditException kerül dobásra (ha false). |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Beszúr egy megadott forrásdia másolatát a gyűjtemény megadott pozíciójába. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott masterből (a megfelelő elrendezés a forrásdia elrendezésével azonos Type vagy Name értékkel rendelkező elrendezés). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout true), vagy PptxEditException kerül dobásra (ha false).

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Másolandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Új dia mastere. |
| allowCloneMissingLayout | boolean | Ha a megadott masterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha true), vagy PptxEditException kerül dobásra (ha false). |

#### Visszatér:
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Eltávolítja a specifikus objektum első előfordulását a gyűjteményből.

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | A gyűjteményből eltávolítandó dia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a gyűjtemény megadott indexű elemét.

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nullától kezdődő indexe. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

#### Visszatér:
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator, amely a gyűjteményen iterálásra használható.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

#### Visszatér:
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator a teljes gyűjteményhez.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Létrehozza és visszaadja a benne lévő összes dia tömbjét.

#### Visszatér:
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) tömbje

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Létrehozza és visszaadja a megadott tartományban lévő összes dia tömbjét.

#### Paraméterek:
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első hozzáadandó dia indexe. |
| count | int | A hozzáadandó diák száma. |

#### Visszatér:
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) tömbje
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Áthelyezi a diát a gyűjteményből a megadott pozícióba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Cél index. |
| slide | [ISlide](../../com.aspose.slides/islide) | Áthelyezendő dia. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Áthelyezi a diákat a gyűjteményből a megadott pozícióba. A diák az indexnél kezdve, a listában megjelenő sorrendben kerülnek elhelyezésre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Cél index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Áthelyezendő diák. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
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
public final ISlide[] addFromPdf(String path)
```

Létrehozza a diákat a PDF dokumentumból, és a gyűjtemény végére adja hozzá.

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
| path | java.lang.String | A PDF dokumentum elérési útja |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Létrehozza a diákat a PDF dokumentumból, és a pdf importálási beállítások figyelembevételével a gyűjtemény végére adja hozzá.

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
| path | java.lang.String | A PDF dokumentum elérési útja |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Pdf importálási beállítások |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Létrehozza a diákat a PDF dokumentumból, és a gyűjtemény végére adja hozzá.

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
| pdfStream | java.io.InputStream | A PDF dokumentum forrásaként használandó adatfolyam |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Létrehozza a diákat a PDF dokumentumból, és a pdf importálási beállítások figyelembevételével a gyűjtemény végére adja hozzá.

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
| pdfStream | java.io.InputStream | A PDF dokumentum forrásaként használandó adatfolyam |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Pdf importálási beállítások |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | java.lang.String | Hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | java.lang.String | Hozzáadandó HTML. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Olyan Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény végére adja hozzá.

--------------------

> ```
> // Létrehozza a Presentation osztály egy példányát.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // Meghívja az AddFromHtml metódust és átadja a HTML fájlt.
>      pres.getSlides().addFromHtml(html);
>      // A Save metódust használja a fájl PowerPoint dokumentumként történő mentéséhez.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Olyan Stream objektum, amely a HTML fájl forrásaként szolgál. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Létrehozza a diákat HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrandó pozíció. |
| htmlText | java.lang.String | Hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Létrehozza a diákat HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrandó pozíció. |
| htmlText | java.lang.String | Hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diával vagy a megadott indexű diával. Ha **true**, akkor az adatbeszúrás a megadott indexű diához tartozó üres területen indul. Ha **false**, akkor az adat a létrehozott diákhoz lesz hozzáadva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Létrehozza a diákat HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrandó pozíció. |
| htmlText | java.lang.String | Hozzáadandó HTML. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Létrehozza a diákat HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrandó pozíció. |
| htmlText | java.lang.String | Hozzáadandó HTML. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diával vagy a megadott indexű diával. Ha **true**, akkor az adatbeszúrás a megadott indexű diához tartozó üres területen indul. Ha **false**, akkor az adat a létrehozott diákhoz lesz hozzáadva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Létrehozza a diákat HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrandó pozíció. |
| htmlStream | java.io.InputStream | Olyan Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Létrehozza a diákat HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrandó pozíció. |
| htmlStream | java.io.InputStream | Olyan Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívási objektum. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül marad. |
| uri | java.lang.String | A megadott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diával vagy a megadott indexű diával. Ha **true**, akkor az adatbeszúrás a megadott indexű diához tartozó üres területen indul. Ha **false**, akkor az adat a létrehozott diákhoz lesz hozzáadva. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Létrehozza a diákat HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrandó pozíció. |
| htmlStream | java.io.InputStream | Olyan Stream objektum, amely a HTML fájl forrásaként szolgál. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Létrehozza a diákat HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrandó pozíció. |
| htmlStream | java.io.InputStream | Olyan Stream objektum, amely a HTML fájl forrásaként szolgál. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diával vagy a megadott indexű diával. Ha **true**, akkor az adatbeszúrás a megadott indexű diához tartozó üres területen indul. Ha **false**, akkor az adat a létrehozott diákhoz lesz hozzáadva. |

**Visszatérési érték:**
com.aspose.slides.ISSlide[] - Hozzáadott diák

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Másolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object