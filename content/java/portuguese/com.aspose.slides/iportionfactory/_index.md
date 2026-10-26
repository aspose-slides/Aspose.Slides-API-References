---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Permite criar trechos de teste
type: docs
url: /pt/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Permite criar trechos de teste

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Cria um trecho de texto vazio.

**Retorna:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Cria um trecho de texto a partir da string especificada.

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


Cria um portion com o uso de dados de um portion especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Um portion a ser usado. |

**Retorna:**
[IPortion](../../com.aspose.slides/iportion) - Portion.