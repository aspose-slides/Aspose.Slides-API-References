---
title: IPortionFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar porções de teste
type: docs
url: /pt/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Permite criar porções de teste

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createPortion()](#createPortion--) | Cria uma porção de texto vazia. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Cria uma porção de texto a partir da string especificada. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Cria uma porção usando os dados de uma porção especificada. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Cria uma porção de texto vazia.

**Retorna:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Cria uma porção de texto a partir da string especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | java.lang.String | String. |

**Retorna:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Cria uma porção usando os dados de uma porção especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Uma porção a ser usada. |

**Retorna:**
[IPortion](../../com.aspose.slides/iportion) - Portion.