---
title: BaseSlide
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta i dati comuni per tutti i tipi di diapositiva.
type: docs
url: /it/com.aspose.slides/baseslide/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Rappresenta dati comuni per tutti i tipi di diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShapes()](#getShapes--) | Restituisce le forme di una diapositiva. |
| [getControls()](#getControls--) | Restituisce la collezione di controlli ActiveX su una diapositiva. |
| [getName()](#getName--) | Restituisce o imposta il nome di una diapositiva. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce o imposta il nome di una diapositiva. |
| [getSlideId()](#getSlideId--) | Restituisce l'ID di una diapositiva. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Determina se le due istanze di IBaseSlide sono uguali. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce i run con lo stesso formato in tutti i paragrafi di tutte le forme accettabili. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Unisce i run con lo stesso formato in tutti i paragrafi di tutte le forme accettabili. |
| [createThemeEffective()](#createThemeEffective--) | Restituisce un tema efficace per questa diapositiva. |
| [getCustomData()](#getCustomData--) | Restituisce i dati personalizzati della diapositiva. |
| [getTimeline()](#getTimeline--) | Restituisce l'oggetto della timeline di animazione. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Restituisce l'oggetto Transition che contiene informazioni su come la diapositiva specificata avanza durante una presentazione. |
| [getBackground()](#getBackground--) | Restituisce lo sfondo della diapositiva. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornisce un accesso facile ai collegamenti ipertestuali contenuti. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Restituisce l'interfaccia IPresentation. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Restituisce le forme di una diapositiva. Solo lettura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Restituisce:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Restituisce la collezione di controlli ActiveX su una diapositiva. Solo lettura [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Restituisce:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Restituisce o imposta il nome di una diapositiva. Lettura / scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Restituisce o imposta il nome di una diapositiva. Lettura / scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Restituisce l'ID di una diapositiva. Solo lettura long.

**Restituisce:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Determina se le due istanze di IBaseSlide sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad esempio SlideId, e del contenuto dinamico, ad esempio il valore corrente della data in un segnaposto Data.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | L'IBaseSlide da confrontare con l'IBaseSlide corrente. |

**Restituisce:**
boolean -  **true**  se l'IBaseSlide specificato è uguale all'IBaseSlide corrente; altrimenti,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Unisce i run con lo stesso formato in tutti i paragrafi di tutte le forme accettabili.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Unisce i run con lo stesso formato in tutti i paragrafi di tutte le forme accettabili.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Restituisce un tema efficace per questa diapositiva.

**Restituisce:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Restituisce i dati personalizzati della diapositiva. Solo lettura [ICustomData](../../com.aspose.slides/icustomdata).

**Restituisce:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Restituisce l'oggetto della timeline di animazione. Solo lettura [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Restituisce:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Restituisce l'oggetto Transition che contiene informazioni su come la diapositiva specificata avanza durante una presentazione. Solo lettura [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Restituisce:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Restituisce lo sfondo della diapositiva. Solo lettura [IBackground](../../com.aspose.slides/ibackground).

**Restituisce:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Fornisce un accesso facile ai collegamenti ipertestuali contenuti. Solo lettura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Restituisce:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Specifică se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Lettura / scrittura boolean.

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Specifică se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Lettura / scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Trova la prima occorrenza di una forma con il testo alternativo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| altText | java.lang.String | Testo alternativo. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - oggetto Shape o null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce l'interfaccia IPresentation. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva base. Solo lettura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)