---
title: HandleRepeatedSpaces
second_title: Referência da API Aspose.Slides para Java
description: Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown.
type: docs
url: /pt/com.aspose.slides/handlerepeatedspaces/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown.
## Campos

| Campo | Descrição |
| --- | --- |
| [None](#None) | Todos os espaços são preservados como caracteres de espaço regulares sem nenhuma alteração. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Converte sequências de dois ou mais espaços regulares consecutivos alternando entre caracteres de espaço regulares e entidades de espaço não-quebrável NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Converte sequências de dois ou mais espaços regulares consecutivos preservando o primeiro espaço como um caractere de espaço regular e substituindo todos os espaços subsequentes por entidades de espaço não-quebrável NBSP. |
### None {#None}
```
public static final int None
```


Todos os espaços são preservados como caracteres de espaço regulares sem nenhuma alteração. Nenhuma transformação é aplicada, e múltiplos espaços consecutivos são exportados como estão.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Converte sequências de dois ou mais espaços regulares consecutivos alternando entre caracteres de espaço regulares e entidades de espaço não-quebrável NBSP. O primeiro espaço é sempre preservado como um espaço regular.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Converte sequências de dois ou mais espaços regulares consecutivos preservando o primeiro espaço como um caractere de espaço regular e substituindo todos os espaços subsequentes por entidades de espaço não-quebrável NBSP.