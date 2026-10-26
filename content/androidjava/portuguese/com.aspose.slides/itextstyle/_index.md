---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Text style formatting properties.
type: docs
url: /pt/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Propriedades de formatação de estilo de texto.

## Métodos

| Método | Descrição |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Se o nível de estilo existir, retorna-o; caso contrário, retorna null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Propriedades padrão do parágrafo. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de estilo de texto efetivos com a herança aplicada. |

### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Se o nível de estilo existir, retorna-o; caso contrário, retorna null.

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

Obtém os dados de formatação de estilo de texto efetivos com a herança aplicada.

**Retorna:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Um [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).