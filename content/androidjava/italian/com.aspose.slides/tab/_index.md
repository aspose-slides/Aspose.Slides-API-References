---
title: Tab
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una tabulazione per un testo.
type: docs
url: /it/com.aspose.slides/tab/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Rappresenta una tabulazione per un testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Crea una nuova Tab |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione di una tabulazione. |
| [setPosition(double value)](#setPosition-double-) | Restituisce o imposta la posizione di una tabulazione. |
| [getAlignment()](#getAlignment--) | Restituisce o imposta lo stile di allineamento di una tabulazione. |
| [setAlignment(int value)](#setAlignment-int-) | Restituisce o imposta lo stile di allineamento di una tabulazione. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Confronta l'istanza corrente con un altro oggetto dello stesso tipo. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Crea una nuova Tab

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | double | Posizione della tabulazione. |
| align | int | Allineamento. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Sola lettura long.

**Restituisce:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Restituisce o imposta la posizione di una tabulazione. Assegnare questa proprietà può cambiare l'indice della tabulazione nella collezione e invalidare l'Enumerator. Lettura/scrittura double.

**Restituisce:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Restituisce o imposta la posizione di una tabulazione. Assegnare questa proprietà può cambiare l'indice della tabulazione nella collezione e invalidare l'Enumerator. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Restituisce o imposta lo stile di allineamento di una tabulazione. Lettura/scrittura [TabAlignment](../../com.aspose.slides/tabalignment).

**Restituisce:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Restituisce o imposta lo stile di allineamento di una tabulazione. Lettura/scrittura [TabAlignment](../../com.aspose.slides/tabalignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Confronta l'istanza corrente con un altro oggetto dello stesso tipo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un oggetto da confrontare con questa istanza. |

**Restituisce:**
int - Un intero a 32-bit che indica l'ordine relativo dei comparandi. Il valore di ritorno ha i seguenti significati:

 *  < 0 - Questa istanza è inferiore a obj.
 *  = 0 - Questa istanza è uguale a obj.
 *  > 0 - Questa istanza è maggiore di obj.