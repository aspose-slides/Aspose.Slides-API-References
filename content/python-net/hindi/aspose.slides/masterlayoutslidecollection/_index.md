---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection क्लास

परिभाषित मास्टर स्लाइड के सभी लेआउट स्लाइडों का संग्रह दर्शाता है।
            LayoutSlideCollection क्लास को विस्तारित करता है जिसमें व्यक्तिगत मास्टर लेआउट स्लाइडों के संग्रह के संदर्भ में लेआउट स्लाइड जोड़ने/डालने/हटाने/कॉपी बनाने/पुनः व्यवस्थित करने के तरीके शामिल हैं।

**Inheritance:**[`MasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/hi/aspose.slides/layoutslidecollection)

The MasterLayoutSlideCollection type exposes the following members:

## इंडेक्सर

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## मेथड्स

| Method | Description |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | निर्दिष्ट प्रकार की पहली लेआउट स्लाइड लौटाता है।<br/>            खोजने के लिए लेआउट स्लाइड का प्रकार।[`LayoutSlide`](/slides/python-net/hi/aspose.slides/layoutslide) निर्दिष्ट प्रकार के साथ या यदि कोई लेआउट नहीं मिला तो None। |
| [`remove(self, value)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | संग्रह से एक लेआउट को हटाता है। |
| [`remove_unused(self)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/remove_unused/#) | अप्रयुक्त लेआउट स्लाइडों को हटाता है (जिनकी HasDependingSlides गलत है)। |
| [`add_clone(self, source_layout)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | निर्दिष्ट लेआउट स्लाइड की एक कॉपी को संग्रह के अंत में जोड़ता है। |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | निर्दिष्ट लेआउट स्लाइड की एक कॉपी को संग्रह में निर्दिष्ट स्थान पर डालता है। |
| [`add(self, layout_type, layout_name)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | एक नई लेआउट स्लाइड को संग्रह के अंत में जोड़ता है। |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | एक नई लेआउट स्लाइड को संग्रह में निर्दिष्ट स्थान पर डालता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/remove_at/#int) | संग्रह में निर्दिष्ट सूचकांक पर स्थित तत्व को हटाता है। |
| [`reorder(self, index, layout_slide)`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | लेआउट स्लाइड को संग्रह से हटाकर निर्दिष्ट स्थान पर ले जाता है। |


### और देखें
* क्लास [`LayoutSlideCollection`](/slides/python-net/hi/aspose.slides/layoutslidecollection)
* क्लास [`MasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/masterlayoutslidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)