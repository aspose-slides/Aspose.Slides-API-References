---
title: IMathBlock
second_title: Tham khảo API Aspose.Slides cho Java
description: Xác định một thể hiện của văn bản toán học nằm trong MathParagraph và bắt đầu trên một dòng riêng.
type: docs
url: /vi/com.aspose.slides/imathblock/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Xác định một thể hiện của văn bản toán học nằm trong MathParagraph và bắt đầu trên một dòng riêng. Tất cả các vùng toán học, bao gồm các phương trình, biểu thức, mảng phương trình hoặc biểu thức và công thức đều được biểu diễn bằng khối toán học.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Phân định tất cả các phần tử con bằng ký tự phân cách (không kèm dấu ngoặc) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Bao bọc các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung và phân định bằng ký tự phân cách |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Kết hợp một khối toán học khác với khối này |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Lưu nội dung của [IMathBlock](../../com.aspose.slides/imathblock) này dưới dạng MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Phân định tất cả các phần tử con bằng ký tự phân cách (không kèm dấu ngoặc)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| separatorCharacter | char | Ký tự được sử dụng làm dấu phân cách |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phiên bản của phần tử IMathDelimiter element
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Bao bọc các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung và phân định bằng ký tự phân cách

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| beginningCharacter | char | Ký tự bắt đầu (thường là dấu ngoặc trái) |
| endingCharacter | char | Ký tự kết thúc (thường là dấu ngoặc phải) |
| separatorCharacter | char | Ký tự phân cách |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phần tử toán học loại [IMathDelimiter](../../com.aspose.slides/imathdelimiter) bao gồm các ký tự được chỉ định làm khung và dấu phân cách
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Kết hợp một khối toán học khác với khối này

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Khối đang được ghép |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - this mathematical block after joining
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Lưu nội dung của [IMathBlock](../../com.aspose.slides/imathblock) này dưới dạng MathML

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |