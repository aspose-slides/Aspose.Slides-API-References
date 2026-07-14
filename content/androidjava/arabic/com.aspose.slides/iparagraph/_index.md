---
title: IParagraph
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل فقرة من نص.
type: docs
url: /ar/com.aspose.slides/iparagraph/
---
**جميع الواجهات المنفذة:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

يمثل فقرة من نص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPortions()](#getPortions--) | إرجاع مجموعة أجزاء النص. |
| [getParagraphFormat()](#getParagraphFormat--) | إرجاع كائن التنسيق لهذه الفقرة. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دمج المقاطع التي لها نفس التنسيق. |
| [getText()](#getText--) | الحصول أو تعيين النص العادي للفقرة. |
| [setText(String value)](#setText-java.lang.String-) | الحصول أو تعيين النص العادي للفقرة. |
| [getRect()](#getRect--) | الحصول على إحداثيات المستطيل الذي يحد الفقرة. |
| [getLinesCount()](#getLinesCount--) | الحصول على عدد الأسطر في الفقرة. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | تحديد خصائص الجزء الذي سيُستخدم إذا تم إدراج جزء آخر بعد الأخير. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | تحديد خصائص الجزء الذي سيُستخدم إذا تم إدراج جزء آخر بعد الأخير. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

إرجاع مجموعة أجزاء النص. للقراءة فقط [IPortionCollection](../../com.aspose.slides/iportioncollection).

**القيمة المرجعة:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

إرجاع كائن التنسيق لهذه الفقرة. للقراءة فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**القيمة المرجعة:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

دمج المقاطع التي لها نفس التنسيق.
### getText() {#getText--}
```
public abstract String getText()
```

الحصول على النص العادي للفقرة أو تعيينه. قابل للقراءة والكتابة String.

القيمة: النص.

**القيمة المرجعة:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

الحصول على النص العادي للفقرة أو تعيينه. قابل للقراءة والكتابة String.

القيمة: النص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

الحصول على إحداثيات المستطيل الذي يحد الفقرة. يشمل المستطيل جميع أسطر النص في الفقرة، بما في ذلك الفارغة.

**القيمة المرجعة:**
android.graphics.RectF - المستطيل الذي يحد الفقرة android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

الحصول على عدد الأسطر في الفقرة.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
int - عدد الأسطر في الفقرة
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

تحديد خصائص الجزء الذي سيُستخدم إذا تم إدراج جزء آخر بعد الأخير.

**القيمة المرجعة:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

تحديد خصائص الجزء الذي سيُستخدم إذا تم إدراج جزء آخر بعد الأخير.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |