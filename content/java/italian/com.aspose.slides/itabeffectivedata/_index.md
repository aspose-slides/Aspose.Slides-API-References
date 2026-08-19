---
title: ITabEffectiveData
second_title: Riferimento API di Aspose.Slides per Java
description: Oggetto immutabile che contiene le proprietà di stop di tabulazione del testo efficace.
type: docs
url: /it/com.aspose.slides/itabeffectivedata/
---
**Tutte le interfacce implementate:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Oggetto immutabile che contiene le proprietà di tabulazione del testo efficace.

--------------------

Questa interfaccia è usata come parte di [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPosition()](#getPosition--) | Restituisce la posizione di un tab. |
| [getAlignment()](#getAlignment--) | Restituisce lo stile di allineamento di un tab. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Restituisce la posizione di un tab. Assegnare questa proprietà può modificare l'indice del tab nella raccolta e invalidare l'Enumerator. Sola lettura double.

**Restituisce:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Restituisce lo stile di allineamento di un tab. Sola lettura [TabAlignment](../../com.aspose.slides/tabalignment).

**Restituisce:**
int