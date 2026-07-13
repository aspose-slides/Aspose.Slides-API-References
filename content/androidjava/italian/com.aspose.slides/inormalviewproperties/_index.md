---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /it/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Rappresenta le proprietà della visualizzazione normale. La visualizzazione normale è composta da tre regioni di contenuto: la diapositiva stessa, una regione di contenuto laterale e una regione di contenuto inferiore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Specifica se l'applicazione deve mostrare icone durante la visualizzazione del contenuto dello schema in una qualsiasi delle regioni di contenuto della modalità visualizzazione normale. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Specifica se l'applicazione deve mostrare icone durante la visualizzazione del contenuto dello schema in una qualsiasi delle regioni di contenuto della modalità visualizzazione normale. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Specifica se il divisore verticale dovrebbe bloccare in uno stato minimizzato quando la regione laterale è sufficientemente piccola. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Specifica se il divisore verticale dovrebbe bloccare in uno stato minimizzato quando la regione laterale è sufficientemente piccola. |
| [getVerticalBarState()](#getVerticalBarState--) | Specifica lo stato in cui la barra del divisore verticale dovrebbe essere visualizzata. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Specifica lo stato in cui la barra del divisore verticale dovrebbe essere visualizzata. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Specifica lo stato in cui la barra del divisore orizzontale dovrebbe essere visualizzata. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Specifica lo stato in cui la barra del divisore orizzontale dovrebbe essere visualizzata. |
| [getPreferSingleView()](#getPreferSingleView--) | Specifica se l'utente preferisce vedere una singola regione di contenuto a finestra intera rispetto alla visualizzazione normale standard con tre regioni di contenuto. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Specifica se l'utente preferisce vedere una singola regione di contenuto a finestra intera rispetto alla visualizzazione normale standard con tre regioni di contenuto. |
| [getRestoredLeft()](#getRestoredLeft--) | Questo elemento specifica le dimensioni della regione di contenuto laterale della visualizzazione normale, quando la regione ha una dimensione restaurata variabile (né minimizzata né massimizzata). |
| [getRestoredTop()](#getRestoredTop--) | Questo elemento specifica le dimensioni della regione superiore della diapositiva nella visualizzazione normale, quando la regione ha una dimensione restaurata variabile (né minimizzata né massimizzata). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Specifică se l'applicazione deve mostrare icone durante la visualizzazione del contenuto dello schema in una qualsiasi delle regioni di contenuto della modalità visualizzazione normale. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Specifică se l'applicazione deve mostrare icone durante la visualizzazione del contenuto dello schema in una qualsiasi delle regioni di contenuto della modalità visualizzazione normale. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Specifică se il divisore verticale dovrebbe bloccare in uno stato minimizzato quando la regione laterale è sufficientemente piccola. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Specifică se il divisore verticale dovrebbe bloccare in uno stato minimizzato quando la regione laterale è sufficientemente piccola. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Specifică lo stato in cui la barra del divisore verticale dovrebbe essere visualizzata. Una barra del divisore verticale separa la diapositiva dalla regione di contenuto laterale.

**Restituisce:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Specifică lo stato in cui la barra del divisore verticale dovrebbe essere visualizzata. Una barra del divisore verticale separa la diapositiva dalla regione di contenuto laterale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Specifică lo stato in cui la barra del divisore orizzontale dovrebbe essere visualizzata. Una barra del divisore orizzontale separa la diapositiva dalla regione di contenuto sotto la diapositiva.

**Restituisce:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Specifică lo stato in cui la barra del divisore orizzontale dovrebbe essere visualizzata. Una barra del divisore orizzontale separa la diapositiva dalla regione di contenuto sotto la diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Specifică se l'utente preferisce vedere una singola regione di contenuto a finestra intera rispetto alla visualizzazione normale standard con tre regioni di contenuto. Se abilitato, l'applicazione può scegliere di visualizzare una delle regioni di contenuto nell'intera finestra. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Specifică se l'utente preferisce vedere una singola regione di contenuto a finestra intera rispetto alla visualizzazione normale standard con tre regioni di contenuto. Se abilitato, l'applicazione può scegliere di visualizzare una delle regioni di contenuto nell'intera finestra. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Questo elemento specifica le dimensioni della regione di contenuto laterale della visualizzazione normale, quando la regione è di una dimensione restaurata variabile (né minimizzata né massimizzata). Solo lettura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Restituisce:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Questo elemento specifica le dimensioni della regione superiore della diapositiva nella visualizzazione normale, quando la regione è di una dimensione restaurata variabile (né minimizzata né massimizzata). Solo lettura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Restituisce:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)