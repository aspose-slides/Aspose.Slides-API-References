---
title: IMathBlock
second_title: Aspose.Slides для Android через справочник API Java
description: Определяет экземпляр математического текста, содержащегося в MathParagraph и начинающегося с новой строки.
type: docs
url: /ru/com.aspose.slides/imathblock/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Определяет экземпляр математического текста, содержащегося в MathParagraph и начинающегося с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены математическим блоком.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Методы

| Метод | Описание |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Разделяет все дочерние элементы символом-разделителем (без скобок) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Охватывает дочерние элементы этого блока указанными символами, например скобками или другими, в качестве рамки и разделяет их символом-разделителем |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Объединяет другой математический блок с этим |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Сохраняет содержимое этого [IMathBlock](../../com.aspose.slides/imathblock) в формате MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Разделяет все дочерние элементы символом-разделителем (без скобок)

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
| separatorCharacter | char | Символ, используемый в качестве разделителя |

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Экземпляр элемента IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


Охватывает дочерние элементы этого блока указанными символами, например скобками или другими, в качестве рамки и разделяет их символом-разделителем

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char | Начальный символ (обычно левая скобка) |
| endingCharacter | char | Конечный символ (обычно правая скобка) |
| separatorCharacter | char | Символ-разделитель |

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Математический элемент типа [IMathDelimiter](../../com.aspose.slides/imathdelimiter), включающий указанные символы в качестве рамки и разделителя
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```


Объединяет другой математический блок с этим

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Блок, который присоединяется |

**Возвращает:**
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