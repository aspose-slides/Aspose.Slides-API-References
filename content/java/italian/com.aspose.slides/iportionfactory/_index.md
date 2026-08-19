---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Consente di creare porzioni di test
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
| [createPortion()](#createPortion--) | Crea una Portion di testo vuota. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Crea una Portion di testo dalla stringa specificata. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Crea una Portion usando i dati di una Portion specificata. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Crea una Portion di testo vuota.

**Restituisce:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Crea una Portion di testo dalla stringa specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | java.lang.String | String. |

**Restituisce:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Crea una Portion usando i dati di una Portion specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Una Portion da usare. |

**Restituisce:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.