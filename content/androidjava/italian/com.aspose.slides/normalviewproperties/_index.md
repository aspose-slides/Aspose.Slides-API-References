---
title: NormalViewProperties
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta le proprietà della visualizzazione normale.
type: docs
url: /it/com.aspose.slides/normalviewproperties/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Rappresenta le proprietà della visualizzazione normale. La visualizzazione normale è composta da tre regioni di contenuto: la diapositiva stessa, una regione di contenuto laterale e una regione di contenuto inferiore.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Instanziare un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Specifica se l'applicazione deve mostrare le icone quando visualizza il contenuto della struttura in una qualsiasi delle regioni di contenuto della modalità visualizzazione normale. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Specifica se l'applicazione deve mostrare le icone quando visualizza il contenuto della struttura in una qualsiasi delle regioni di contenuto della modalità visualizzazione normale. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Specifica se il divisore verticale deve agganciarsi a uno stato ridotto quando la regione laterale è sufficientemente piccola. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Specifica se il divisore verticale deve agganciarsi a uno stato ridotto quando la regione laterale è sufficientemente piccola. |
| [getVerticalBarState()](#getVerticalBarState--) | Specifica lo stato in cui la barra del divisore verticale deve essere visualizzata. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Specifica lo stato in cui la barra del divisore verticale deve essere visualizzata. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Specifica lo stato in cui la barra del divisore orizzontale deve essere visualizzata. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Specifica lo stato in cui la barra del divisore orizzontale deve essere visualizzata. |
| [getPreferSingleView()](#getPreferSingleView--) | Specifica se l'utente preferisce vedere una singola regione di contenuto a pieno schermo rispetto alla visualizzazione normale standard con tre regioni di contenuto. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Specifica se l'utente preferisce vedere una singola regione di contenuto a pieno schermo rispetto alla visualizzazione normale standard con tre regioni di contenuto. |
| [getRestoredLeft()](#getRestoredLeft--) | Questo elemento specifica le dimensioni della regione di contenuto laterale della visualizzazione normale, quando la regione è di dimensione variabile ripristinata (né minimizzata né massimizzata). |
| [getRestoredTop()](#getRestoredTop--) | Questo elemento specifica le dimensioni della regione superiore della diapositiva nella visualizzazione normale, quando la regione è di dimensione variabile ripristinata (né minimizzata né massimizzata). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Specifică se l'applicazione deve mostrare le icone quando visualizza il contenuto della struttura in una qualsiasi delle regioni di contenuto della modalità visualizzazione normale. Booleano leggibile/scrivibile.

**Restituisce:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Specifică se l'applicazione deve mostrare le icone quando visualizza il contenuto della struttura in una qualsiasi delle regioni di contenuto della modalità visualizzazione normale. Booleano leggibile/scrivibile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Specifică se il divisore verticale deve agganciarsi a uno stato ridotto quando la regione laterale è sufficientemente piccola. Booleano leggibile/scrivibile.

**Restituisce:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Specifică se il divisore verticale deve agganciarsi a uno stato ridotto quando la regione laterale è sufficientemente piccola. Booleano leggibile/scrivibile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Specifică lo stato in cui la barra del divisore verticale deve essere visualizzata. Una barra del divisore verticale separa la diapositiva dalla regione di contenuto laterale.

**Restituisce:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Specifică lo stato in cui la barra del divisore verticale deve essere visualizzata. Una barra del divisore verticale separa la diapositiva dalla regione di contenuto laterale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Specifică lo stato in cui la barra del divisore orizzontale deve essere visualizzata. Una barra del divisore orizzontale separa la diapositiva dalla regione di contenuto sotto la diapositiva.

**Restituisce:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Specifică lo stato in cui la barra del divisore orizzontale deve essere visualizzata. Una barra del divisore orizzontale separa la diapositiva dalla regione di contenuto sotto la diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Specifică se l'utente preferisce vedere una singola regione di contenuto a pieno schermo rispetto alla visualizzazione normale standard con tre regioni di contenuto. Se abilitato, l'applicazione può scegliere di visualizzare una delle regioni di contenuto nell'intera finestra. Booleano leggibile/scrivibile.

**Restituisce:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Specifică se l'utente preferisce vedere una singola regione di contenuto a pieno schermo rispetto alla visualizzazione normale standard con tre regioni di contenuto. Se abilitato, l'applicazione può scegliere di visualizzare una delle regioni di contenuto nell'intera finestra. Booleano leggibile/scrivibile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Questo elemento specifica le dimensioni della regione di contenuto laterale della visualizzazione normale, quando la regione è di dimensione variabile ripristinata (né minimizzata né massimizzata). Solo lettura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Restituisce:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Questo elemento specifica le dimensioni della regione superiore della diapositiva nella visualizzazione normale, quando la regione è di dimensione variabile ripristinata (né minimizzata né massimizzata). Solo lettura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Restituisce:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)