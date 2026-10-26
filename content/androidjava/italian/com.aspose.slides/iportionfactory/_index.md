---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /it/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Consente di creare porzioni di test

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createPortion()](#createPortion--) | Crea una porzione di testo vuota. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Crea una porzione di testo da una stringa specificata. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Crea una porzione usando i dati di una porzione specificata. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Crea una porzione di testo vuota.

**Restituisce:**
[IPortion](../../com.aspose.slides/iportion) - Porzione.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Crea una porzione di testo da una stringa specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | java.lang.String | Stringa. |

**Restituisce:**
[IPortion](../../com.aspose.slides/iportion) - Porzione.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Crea una porzione usando i dati di una porzione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Una porzione da utilizzare. |

**Restituisce:**
[IPortion](../../com.aspose.slides/iportion) - Porzione.