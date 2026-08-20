---
title: GetImage()
second_title: Aspose.Slides for C++ API Reference
description: Returns an image of the paragraph.
type: docs
weight: 118
url: /aspose.slides/iparagraph/getimage/
---
## IParagraph::GetImage() method


Returns an image of the paragraph.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IParagraph::GetImage()=0
```


### Return Value

An image containing the rendered paragraph, or **null**
## Remarks



if the paragraph cannot be found in its parent collection, has no valid rendering bounds, or an error occurs while rendering the image. 

The following example shows how to render a paragraph as an image: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = pres->get_Slide(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 50.0f, 50.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> paragraph = shape->get_TextFrame()->get_Paragraph(0);
paragraph->set_Text(u"Aspose Paragraph GetImage() Example");

System::SharedPtr<IImage> paragraphImage = paragraph->GetImage();
paragraphImage->Save(u"paragraph.png");
```




## IParagraph::GetImage(float, float) method


Returns an image of the paragraph with the specified scale.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IParagraph::GetImage(float scaleX, float scaleY)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | **float** | The horizontal scale factor applied to the paragraph image. |
| scaleY | **float** | The vertical scale factor applied to the paragraph image. |

### Return Value

An image containing the rendered paragraph, or **null**
## Remarks



if the paragraph cannot be found in its parent collection, has no valid rendering bounds, or an error occurs while rendering the image. 

The following example shows how to render each text box paragraph on a slide as an image with custom scaling: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

int shapeIndex = 0;

for (auto&& shape : slide->get_Shapes())
{
    System::SharedPtr<IAutoShape> autoShape = System::AsCast<IAutoShape>(shape);
    if (autoShape == nullptr)
    {
        continue;
    }

    int paragraphIndex = 0;
    for (auto&& paragraph : autoShape->get_TextFrame()->get_Paragraphs())
    {
        paragraphIndex++;
        System::SharedPtr<IImage> paragraphImage = paragraph->GetImage(2.0f, 2.0f);
        paragraphImage->Save(System::String::Format(u"shape{0}_paragraph{1}.png", shapeIndex, paragraphIndex));
    }
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IParagraph](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)