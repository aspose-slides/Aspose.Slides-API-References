---
title: IBaseSlide
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta i dati comuni per tutti i tipi di diapositiva.
type: docs
url: /it/com.aspose.slides/ibaseslide/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Rappresenta i dati comuni per tutti i tipi di diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShapes()](#getShapes--) | Restituisce le forme di una diapositiva. |
| [getControls()](#getControls--) | Restituisce la collezione di controlli ActiveX su una diapositiva. |
| [getName()](#getName--) | Restituisce o imposta il nome di una diapositiva. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce o imposta il nome di una diapositiva. |
| [getSlideId()](#getSlideId--) | Restituisce l'ID di una diapositiva. |
| [getCustomData()](#getCustomData--) | Restituisce i dati personalizzati della diapositiva. |
| [getTimeline()](#getTimeline--) | Restituisce l'oggetto timeline dell'animazione. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Restituisce l'oggetto TransitionEx che contiene informazioni su come la diapositiva specificata avanza durante una presentazione. |
| [getBackground()](#getBackground--) | Restituisce lo sfondo della diapositiva. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornisce un accesso semplice ai collegamenti ipertestuali contenuti. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla diapositiva master debbano essere mostrate sulle diapositive o meno. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla diapositiva master debbano essere mostrate sulle diapositive o meno. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce le porzioni con lo stesso formato in tutti i paragrafi in tutte le forme accettabili. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Determina se le due istanze di IBaseSlide sono uguali. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


Restituisce le forme di una diapositiva. Solo lettura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Restituisce:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


Restituisce la collezione di controlli ActiveX su una diapositiva. Solo lettura [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Restituisce:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


Restituisce o imposta il nome di una diapositiva. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Restituisce o imposta il nome di una diapositiva. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


Restituisce l'ID di una diapositiva. Solo lettura long.

**Restituisce:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Restituisce i dati personalizzati della diapositiva. Solo lettura [ICustomData](../../com.aspose.slides/icustomdata).

**Restituisce:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


Restituisce l'oggetto timeline dell'animazione. Solo lettura [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Restituisce:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


Restituisce l'oggetto TransitionEx che contiene informazioni su come la diapositiva specificata avanza durante una presentazione. Solo lettura [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Restituisce:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


Restituisce lo sfondo della diapositiva. Solo lettura [IBackground](../../com.aspose.slides/ibackground).

**Restituisce:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Fornisce un accesso semplice ai collegamenti ipertestuali contenuti. Solo lettura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Restituisce:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Specifica se le forme sulla diapositiva master debbano essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Specifica se le forme sulla diapositiva master debbano essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


Trova la prima occorrenza di una forma con il testo alternativo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| altText | java.lang.String | Testo alternativo. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - oggetto ShapeEx o null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Unisce le porzioni con lo stesso formato in tutti i paragrafi in tutte le forme accettabili.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


Determina se le due istanze di IBaseSlide sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad esempio SlideId e contenuto dinamico, ad esempio valore della data corrente nel segnaposto Data.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | L'IBaseSlide da confrontare con l'IBaseSlide corrente. |

**Restituisce:**
boolean - **true** se l'IBaseSlide specificato è uguale all'IBaseSlide corrente; altrimenti, **false**.