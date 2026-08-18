---
title: ITextStyle
second_title: Aspose.Slides para Referência da API Java
description: Propriedades de formatação de estilo de texto.
type: docs
url: /pt/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Propriedades de formatação de estilo de texto.

## Métodos

| Método | Descrição |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Se o nível do estilo existir, retorna-o, caso contrário, retorna null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Propriedades padrão do parágrafo. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de estilo de texto efetivo com a herança aplicada. |

### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Se o nível do estilo existir, retorna-o, caso contrário, retorna null.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice baseado em zero do nível. Deve estar no intervalo 0..8. |

**Retorna:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatação do nível [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Propriedades padrão do parágrafo. Somente leitura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retorna:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Obtém dados de formatação de estilo de texto efetivo com a herança aplicada.

**Retorna:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Um [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).