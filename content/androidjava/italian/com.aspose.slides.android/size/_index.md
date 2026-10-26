---
title: Size
second_title: Riferimento API Java per Aspose.Slides per Android
description: Classe per descrivere le dimensioni di larghezza e altezza in un'unità arbitraria.
type: docs
url: /it/com.aspose.slides.android/size/
---
**Ereditarietà:**
java.lang.Object
```
public class Size
```

Classe per descrivere le dimensioni di larghezza e altezza in un'unità arbitraria.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Crea una nuova istanza di Size. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'oggetto Size. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'oggetto Size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se questa dimensione è uguale a un'altra dimensione. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Restituisce la dimensione rappresentata come stringa nel formato "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Crea una nuova istanza di Size.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'oggetto Size |
| height | int | L'altezza dell'oggetto Size |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza dell'oggetto Size.

**Restituisce:**
int - larghezza
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'altezza dell'oggetto Size.

**Restituisce:**
int - altezza
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se questa dimensione è uguale a un'altra dimensione.

Due dimensioni sono uguali se e solo se sia le loro larghezze sia le loro altezze sono uguali.

Un oggetto Size non è mai uguale a nessun altro tipo di oggetto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Restituisce:**
boolean -  true  se gli oggetti erano uguali,  false  altrimenti
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Restituisce:**
int
### toString() {#toString--}
```
public String toString()
```


Restituisce la dimensione rappresentata come stringa nel formato "WxH"

**Restituisce:**
java.lang.String - rappresentazione stringa della dimensione