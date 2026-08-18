---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objeto imutável que contém propriedades de estilo de texto efetivas.
type: docs
url: /pt/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Objeto imutável que contém propriedades de estilo de texto efetivas.

Esta interface é usada juntamente com a interface [ITextStyle](../../com.aspose.slides/itextstyle) para retornar valores de formatação efetivos com herança aplicada.
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

**Retorna:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Formatação efetiva do nível [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Retorna as propriedades de parágrafo padrão efetivas. Somente leitura [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Retorna:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)