---
title: SlideCollection
second_title: Aspose.Slides Androidra Java API hivatkozás útján
description: Egy diák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/slidecollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

A dia gyűjteményt képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben ténylegesen lévő elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | A megadott dia egy másolatát a gyűjtemény végéhez adja hozzá. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | A megadott dia egy másolatát a megadott szakasz végéhez adja hozzá. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | A megadott dia egy másolatát a gyűjtemény megadott pozíciójába szúrja be. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Új üres diát ad a gyűjtemény végéhez. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | A megadott dia egy másolatát a gyűjtemény megadott pozíciójába szúrja be. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | A megadott dia egy másolatát a gyűjtemény végéhez adja hozzá. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | A megadott dia egy másolatát a gyűjtemény megadott pozíciójába szúrja be. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | A megadott forrásdia egy másolatát a gyűjtemény végéhez adja hozzá. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | A megadott forrásdia egy másolatát a gyűjtemény megadott pozíciójába szúrja be. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely a gyűjteményt bejárja. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő diát tartalmazza. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. A diák az indextől kezdődően a listában szereplő sorrendben lesznek elhelyezve. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Visszaad egy indexet a megadott dia a gyűjteményben. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Létrehozza a diákat a PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Létrehozza a diákat a PDF dokumentumból, és a PDF importálási beállításokat figyelembe véve a gyűjtemény végéhez adja őket. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Létrehozza a diákat a PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Létrehozza a diákat a PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjmtényhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |

### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

**Visszatérési érték:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Visszaadja a megadott indexű elemet. Csak olvasható [Slide](../../com.aspose.slides/slide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

A megadott dia egy másolatát a gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia.

--------------------

Amikor egy diát különböző bemutatók között klónozunk, a dia mesterét is lehet klónozni. Egy belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több másolatának létrehozását. A mesterdiák kézi klónozása sem kerül megelőzésre, sem kerül regisztrálásra. Ha nagyobb vezérlést szeretne a klónozási folyamat felett, használja a \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) vagy a \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) metódusokat a diák klónozásához, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) vagy [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) a layoutok klónozásához és [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) a mesterek klónozásához.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

A megadott dia egy másolatát a megadott szakasz végéhez adja hozzá.

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
>      // Most a második szakasz tartalmazza az első dia másolatát.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| section | [ISection](../../com.aspose.slides/isection) | Az új dia szakasza.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

A megadott dia egy másolatát a gyűjtemény megadott pozíciójába szúrja be.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Példányosítsa a Presentation osztályt, amely egy bemutató fájlt képvisel
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Másolja a kívánt diát a diagyűjtemény végére ugyanabban a bemutatóban
>      ISlideCollection slds = pres.getSlides();
>      // Másolja a kívánt diát a megadott indexre ugyanabban a bemutatóban
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Írja a módosított bemutatót a lemegre
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Példányosítsa a Presentation osztályt a forrásbemutató fájl betöltéséhez
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Példányosítsa a Presentation osztályt a cél PPTX-hez (ahová a dia másolásra kerül)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Írja a cél bemutatót a lemegre
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia.

--------------------

Amikor egy diát különböző bemutatók között klónozunk, a dia mesterét is lehet klónozni. Egy belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több másolatának létrehozását. A mesterdiák kézi klónozása sem kerül megelőzésre, sem kerül regisztrálásra. Ha nagyobb vezérlést szeretne a klónozási folyamat felett, használja a \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) vagy a \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) a diák klónozásához és [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) a mesterek klónozásához.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Új üres diát ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia elrendezése.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Hozzáadott dia.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

A megadott dia egy másolatát a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia elrendezése.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

A megadott dia egy másolatát a gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Új dia elrendezése.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

A megadott dia egy másolatát a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Új dia elrendezése.

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

A megadott forrásdia egy másolatát a gyűjtemény végéhez adja hozzá. A megfelelő elrendezés automatikusan lesz kiválasztva a megadott mesterből (a megfelelő elrendezés azonos típusú vagy névű, mint a forrásdia elrendezése). Ha nem található megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException keletkezik (ha az allowCloneMissingLayout hamis).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Új dia mester. |
| allowCloneMissingLayout | boolean | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException keletkezik (ha hamis). |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Új dia.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

A megadott forrásdia egy másolatát a megadott pozícióba szúrja be. A megfelelő elrendezés automatikusan lesz kiválasztva a megadott mesterből (a megfelelő elrendezés azonos típusú vagy névű, mint a forrásdia elrendezése). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException keletkezik (ha hamis).

**Paraméterok:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Új dia mester. |
| allowCloneMissingLayout | boolean | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException keletkezik (ha hamis). |

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide) - Beszúrt dia.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Eltávolítja a megadott objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Az eltávolítandó dia.

### removeAt(int index) {#removeAt-int-}
```
public final void remove(ISlide value)
```

Eltávolítja a megadott indexű elemet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulláról induló indexe.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Visszaad egy felsorolót, amely a gyűjteményt bejárja.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Egy IGenericEnumerator, amely a gyűjteményt bejárja.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Egy java.util.Iterator a teljes gyűjteményhez.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) tömbje

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő diákot tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első hozzáadandó dia indexe. |
| count | int | A hozzáadandó diák száma.

**Visszatérési érték:**
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
| slide | [ISlide](../../com.aspose.slides/islide) | Áthelyezendő dia.

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Áthelyezi a diákot a gyűjteményből a megadott pozícióba. A diák az indextől kezdve a listában megjelenő sorrendben lesznek elhelyezve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Cél index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Áthelyezendő diák.

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Visszaad egy indexet a megadott dia a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Keresendő dia.

**Visszatérési érték:**
int - A dia indexe vagy -1, ha a dia nem ebben a gyűjteményben van.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Létrehozza a diákat a PDF dokumentumból, és a gyűjtemény végéhez adja őket.

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
| path | java.lang.String | A PDF dokumentum elérési útja

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Létrehozza a diákat a PDF dokumentumból, és a PDF importálási beállításokat figyelembe véve a gyűjtemény végéhez adja őket.

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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF importálási beállítások

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Létrehozza a diákat a PDF dokumentumból, és a gyűjtemény végéhez adja őket.

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
| pdfStream | java.io.InputStream | A PDF dokumentum forrásként használt adatfolyam

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Létrehozza a diákat a PDF dokumentumból, és a gyűjtemény végéhez adja őket.

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
| pdfStream | java.io.InputStream | A PDF dokumentum forrásként használt adatfolyam |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF importálási beállítások

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | java.lang.String | Hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívás. Ha ez a paraméter null, minden külső objektum mellőzve lesz. |
| uri | java.lang.String | Az adott HTML URI-je. Relatív hivatkozások feloldásához használható.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | java.lang.String | Hozzáadandó HTML.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | java.io.InputStream | A HTML fájl forrásként használt adatfolyam. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívás. Ha ez a paraméter null, minden külső objektum mellőzve lesz. |
| uri | java.lang.String | Az adott HTML URI-je. Relatív hivatkozások feloldásához használható.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja őket.

--------------------

> ```
> // Példányosítsa a Presentation osztályt.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Hívja meg az AddFromHtml metódust, és adja át a HTML fájlt.
>          pres.getSlides().addFromHtml(fos);
>          // Használja a Save metódust a fájl PowerPoint dokumentumként való mentéséhez.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | java.io.InputStream | A HTML fájl forrásként használt adatfolyam.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrás pozíciója. |
| htmlText | java.lang.String | Hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívás. Ha ez a paraméter null, minden külső objektum mellőzve lesz. |
| uri | java.lang.String | Az adott HTML URI-je. Relatív hivatkozások feloldásához használható.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrás pozíciója. |
| htmlText | java.lang.String | Hozzáadandó HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívás. Ha ez a paraméter null, minden külső objektum mellőzve lesz. |
| uri | java.lang.String | Az adott HTML URI-je. Relatív hivatkozások feloldásához használható. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diától vagy az adott indexű diától. Ha **true**, akkor az adatbeszúrás az adott indexű dián egy üres helyről indul. Ha **false**, akkor az adat a létrehozott diákhoz kerül. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrás pozíciója. |
| htmlText | java.lang.String | Hozzáadandó HTML.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrás pozíciója. |
| htmlText | java.lang.String | Hozzáadandó HTML. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diától vagy az adott indexű diától. Ha **true**, akkor az adatbeszúrás az adott indexű dián egy üres helyről indul. Ha **false**, akkor az adat a létrehozott diákhoz kerül. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrás pozíciója. |
| htmlStream | java.io.InputStream | A HTML fájl forrásként használt adatfolyam. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívás. Ha ez a paraméter null, minden külső objektum mellőzve lesz. |
| uri | java.lang.String | Az adott HTML URI-je. Relatív hivatkozások feloldásához használható.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrás pozíciója. |
| htmlStream | java.io.InputStream | A HTML fájl forrásként használt adatfolyam. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Külső objektumok lekérésére használt visszahívás. Ha ez a paraméter null, minden külső objektum mellőzve lesz. |
| uri | java.lang.String | Az adott HTML URI-je. Relatív hivatkozások feloldásához használható. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diától vagy az adott indexű diától. Ha **true**, akkor az adatbeszúrás az adott indexű dián egy üres helyről indul. Ha **false**, akkor az adat a létrehozott diákhoz kerül. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrás pozíciója. |
| htmlStream | java.io.InputStream | A HTML fájl forrásként használt adatfolyam.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Létrehozza a diákat HTML szövegből, és a gyűjtemény megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beszúrás pozíciója. |
| htmlStream | java.io.InputStream | A HTML fájl forrásként használt adatfolyam. |
| useSlideWithIndexAsStart | boolean | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diától vagy az adott indexű diától. Ha **true**, akkor az adatbeszúrás az adott indexű dián egy üres helyről indul. Ha **false**, akkor az adat a létrehozott diákhoz kerül. |

**Visszatérési érték:**
com.aspose.slides.ISlide[] - Hozzáadott diák

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object