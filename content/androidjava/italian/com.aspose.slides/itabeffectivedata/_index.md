---
title: ITabEffectiveData
second_title: Aspose.Slides per Android via Riferimento API Java
description: Oggetto immutabile che contiene le proprietà degli stop di tabulazione dei testi effettivi.
type: docs
url: /it/com.aspose.slides/itabeffectivedata/
---
**Tutte le interfacce implementate:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Oggetto immutabile che contiene le proprietà degli stop di tabulazione del testo effettivo.

--------------------

Questa interfaccia è usata come parte di [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPosition()](#getPosition--) | Restituisce la posizione di una tabulazione. |
| [getAlignment()](#getAlignment--) | Restituisce lo stile di allineamento di una tabulazione. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Restituisce la posizione di una tabulazione. Assegnare questa proprietà può modificare l'indice della tabulazione nella collezione e invalidare l'Enumerator. Solo lettura double.

**Restituisce:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Restituisce lo stile di allineamento di una tabulazione. Solo lettura [TabAlignment](../../com.aspose.slides/tabalignment).

**Restituisce:**
int