---
title: SizeF
second_title: Riferimento API Java di Aspose.Slides per Android
description: Classe per descrivere le dimensioni di larghezza e altezza in un'unità arbitraria con valori in virgola mobile.
type: docs
url: /it/com.aspose.slides.android/sizef/
---
**Eredità:**
java.lang.Object
```
public class SizeF
```

Classe per descrivere le dimensioni di larghezza e altezza in un'unità arbitraria con valori in virgola mobile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Crea una nuova istanza di SizeF. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Ottieni la larghezza della dimensione. |
| [getHeight()](#getHeight--) | Ottieni l'altezza della dimensione. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se questa dimensione è uguale a un'altra dimensione. |
| [hashCode()](#hashCode--) | {@inheritDoc} |
| [toString()](#toString--) | Restituisce la dimensione rappresentata come stringa con il formato "WxH" |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

Crea una nuova istanza di SizeF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | float | La larghezza della dimensione |
| height | float | L'altezza della dimensione |

### getWidth() {#getWidth--}
```
public float getWidth()
```

Ottieni la larghezza della dimensione.

**Restituisce:**
float - larghezza
### getHeight() {#getHeight--}
```
public float getHeight()
```

Ottieni l'altezza della dimensione.

**Restituisce:**
float - altezza
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Verifica se questa dimensione è uguale a un'altra dimensione.

Due dimensioni sono uguali se e solo se sia le loro larghezze che le loro altezze sono identiche.

A tale scopo, i valori float di larghezza/altezza sono considerati uguali se e solo se il metodo Float\#floatToIntBits(float).floatToIntBits(float) restituisce lo stesso valore int quando applicato a ciascuno.

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

Restituisce la dimensione rappresentata come stringa con il formato "WxH"

**Restituisce:**
java.lang.String - rappresentazione stringa della dimensione