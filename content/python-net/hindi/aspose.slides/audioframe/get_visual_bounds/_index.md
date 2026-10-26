---
title: get_visual_bounds method
second_title: Aspose.Slides Python के लिये .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
रेंडर की गई सामग्री से गणना की गई आकृति की दृश्य सीमाएँ प्राप्त करता है।

### वापसी

A [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं का प्रतिनिधित्व करता है



```python
def get_visual_bounds(self):
    ...
```


### टिप्पणियाँ
The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
These bounds may differ from the shape's model bounds
([`Shape.x`](/slides/python-net/hi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hi/aspose.slides/shape/height))
and may contain negative coordinates if the rendered content extends
beyond the slide origin.
            
The visual bounds take into account rendering-related aspects such as
transformations (for example, rotation), stroke width and joins,
text layout and overflow, SmartArt geometry, and other layout effects
that influence the final rendered appearance of the shape.
            
The returned bounds are not clipped to the slide rectangle.



### देखें
* क्लास [`AudioFrame`](/slides/python-net/hi/aspose.slides/audioframe)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)