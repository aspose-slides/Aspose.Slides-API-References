---
title: PortionFactory
second_title: Riferimento API di Aspose.Slides per Java
description: Consente di creare porzioni di test
type: docs
url: /it/com.aspose.slides/portionfactory/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Consente di creare porzioni di test

--------------------

Per compatibilità COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createPortion()](#createPortion--) | Crea una porzione di testo vuota. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Crea una porzione di testo da una stringa specificata. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Crea una porzione utilizzando i dati di una porzione specificata. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

Crea una porzione di testo vuota.

**Restituisce:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

Crea una porzione di testo da una stringa specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | java.lang.String | Stringa. |

**Restituisce:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

Crea una porzione utilizzando i dati di una porzione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Una porzione da utilizzare. |

**Restituisce:**
[IPortion](../../com.aspose.slides/iportion) - Portion.