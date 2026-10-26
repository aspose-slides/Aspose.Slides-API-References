---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Rappresenta le proprietà della vista normale.
type: docs
url: /it/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Rappresenta le proprietà della vista normale. La vista normale è composta da tre regioni di contenuto: la diapositiva stessa, una regione di contenuto laterale e una regione di contenuto inferiore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Specifica se l'applicazione deve mostrare icone quando visualizza contenuto di struttura in una qualsiasi delle regioni di contenuto della modalità vista normale. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Specifica se l'applicazione deve mostrare icone quando visualizza contenuto di struttura in una qualsiasi delle regioni di contenuto della modalità vista normale. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Specifica se lo splitter verticale deve agganciarsi a uno stato minimizzato quando la regione laterale è sufficientemente piccola. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Specifica se lo splitter verticale deve agganciarsi a uno stato minimizzato quando la regione laterale è sufficientemente piccola. |
| [getVerticalBarState()](#getVerticalBarState--) | Specifica lo stato in cui la barra di divisione verticale dovrebbe essere mostrata. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Specifica lo stato in cui la barra di divisione verticale dovrebbe essere mostrata. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Specifica lo stato in cui la barra di divisione orizzontale dovrebbe essere mostrata. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Specifica lo stato in cui la barra di divisione orizzontale dovrebbe essere mostrata. |
| [getPreferSingleView()](#getPreferSingleView--) | Specifica se l'utente preferisce vedere una regione di contenuto singola a schermo intero anziché la vista normale standard con tre regioni di contenuto. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Specifica se l'utente preferisce vedere una regione di contenuto singola a schermo intero anziché la vista normale standard con tre regioni di contenuto. |
| [getRestoredLeft()](#getRestoredLeft--) | Questo elemento specifica la dimensione della regione di contenuto laterale della vista normale, quando la regione ha una dimensione ripristinata variabile (neppure minimizzata né massimizzata). |
| [getRestoredTop()](#getRestoredTop--) | Questo elemento specifica la dimensione della regione superiore della diapositiva nella vista normale, quando la regione ha una dimensione ripristinata variabile (neppure minimizzata né massimizzata). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Specificа se l'applicazione deve mostrare icone quando visualizza contenuto di struttura in una qualsiasi delle regioni di contenuto della modalità vista normale. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Specificа se l'applicazione deve mostrare icone quando visualizza contenuto di struttura in una qualsiasi delle regioni di contenuto della modalità vista normale. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Specificа se lo splitter verticale deve agganciarsi a uno stato minimizzato quando la regione laterale è sufficientemente piccola. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Specificа se lo splitter verticale deve agganciarsi a uno stato minimizzato quando la regione laterale è sufficientemente piccola. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Specificа lo stato in cui la barra di divisione verticale dovrebbe essere mostrata. Una barra di divisione verticale separa la diapositiva dalla regione di contenuto laterale.

**Restituisce:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Specificа lo stato in cui la barra di divisione verticale dovrebbe essere mostrata. Una barra di divisione verticale separa la diapositiva dalla regione di contenuto laterale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Specificа lo stato in cui la barra di divisione orizzontale dovrebbe essere mostrata. Una barra di divisione orizzontale separa la diapositiva dalla regione di contenuto sotto la diapositiva.

**Restituisce:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Specificа lo stato in cui la barra di divisione orizzontale dovrebbe essere mostrata. Una barra di divisione orizzontale separa la diapositiva dalla regione di contenuto sotto la diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Specificа se l'utente preferisce vedere una regione di contenuto singola a schermo intero anziché la vista normale standard con tre regioni di contenuto. Se abilitato, l'applicazione può scegliere di visualizzare una delle regioni di contenuto nell'intera finestra. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Specificа se l'utente preferisce vedere una regione di contenuto singola a schermo intero anziché la vista normale standard con tre regioni di contenuto. Se abilitato, l'applicazione può scegliere di visualizzare una delle regioni di contenuto nell'intera finestra. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Questo elemento specifica la dimensione della regione di contenuto laterale della vista normale, quando la regione ha una dimensione ripristinata variabile (neppure minimizzata né massimizzata). Solo lettura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Restituisce:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Questo elemento specifica la dimensione della regione superiore della diapositiva nella vista normale, quando la regione ha una dimensione ripristinata variabile (neppure minimizzata né massimizzata). Solo lettura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Restituisce:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)