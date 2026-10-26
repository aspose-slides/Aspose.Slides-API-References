---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text style properties.
type: docs
url: /pt/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Objeto imutável que contém propriedades de estilo de texto efetivas.

--------------------

Esta interface é usada junto com a interface [ITextStyle](../../com.aspose.slides/itextstyle) para retornar valores de formatação efetiva com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Retorna o nível do estilo efetivo. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Retorna as propriedades de parágrafo padrão efetivas. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Retorna o nível do estilo efetivo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice baseado em zero do nível. Deve estar no intervalo 0..8. |

**Retorno:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Formatação efetiva do nível [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Retorna as propriedades de parágrafo padrão efetivas. Somente leitura [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Retorno:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)