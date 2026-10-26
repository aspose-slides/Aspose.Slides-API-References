---
title: IMathBlock
second_title: Справочник API Aspose.Slides для Java
description: Указывает экземпляр математического текста, содержащийся в MathParagraph и начинающийся с новой строки.
type: docs
url: /ru/com.aspose.slides/imathblock/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Указывает экземпляр математического текста, содержащийся в MathParagraph и начинающийся с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены математическим блоком.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Разделяет все дочерние элементы с помощью символа-разделителя (без скобок) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие, в качестве рамки, и разделяет их символом-разделителем |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Объединяет другой математический блок с этим |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Сохраняет содержимое этого [IMathBlock](../../com.aspose.slides/imathblock) в формате MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Разделяет все дочерние элементы с помощью символа-разделителя (без скобок)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorCharacter | char | Символ, используемый как разделитель |

**Возвращаемое значение:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Экземпляр элемента IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие, в качестве рамки, и разделяет их символом-разделителем

--------------------

> ```
> Пример:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char | Символ начала (обычно левая скобка) |
| endingCharacter | char | Символ окончания (обычно правая скобка) |
| separatorCharacter | char | Символ-разделитель |

**Возвращаемое значение:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Математический элемент типа [IMathDelimiter](../../com.aspose.slides/imathdelimiter), включающий указанные символы в качестве рамки и разделителя
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Объединяет другой математический блок с этим

--------------------

> ```
> Пример:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Объединяемый блок |

**Возвращаемое значение:**
[IMathBlock](../../com.aspose.slides/imathblock) - этот математический блок после объединения
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Сохраняет содержимое этого [IMathBlock](../../com.aspose.slides/imathblock) в формате MathML

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |