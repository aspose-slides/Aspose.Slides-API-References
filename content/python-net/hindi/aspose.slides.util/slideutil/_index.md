---
title: SlideUtil class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.util/slideutil/
---
## SlideUtil क्लास

प्रस्तुति में आकृतियों और पाठ को खोजने में मदद करने वाले मेथड्स प्रदान करता है।

SlideUtil प्रकार निम्नलिखित सदस्य प्रदान करता है:

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/hi/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | PPTX प्रस्तुति में वैकल्पिक पाठ द्वारा आकृति ढूँढें। |
| [`find_shape(slide, alt_text)`](/slides/python-net/hi/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | PPTX प्रस्तुति की स्लाइड में वैकल्पिक पाठ द्वारा आकृति ढूँढें। |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/hi/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | स्लाइड पर सभी आकृतियों की स्थिति बदलता है। आकृतियों को स्लाइड की मार्जिन या किनारे के साथ संरेखित करता है<br/>            या उन्हें आपस में सापेक्ष रूप से संरेखित करता है। |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/hi/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | स्लाइड पर चयनित आकृतियों की स्थिति बदलता है। आकृतियों को स्लाइड की मार्जिन या किनारे के साथ संरेखित करता है<br/>             या उन्हें आपस में सापेक्ष रूप से संरेखित करता है। |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/hi/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | समूह आकृति के भीतर सभी आकृतियों की स्थिति बदलता है। आकृतियों को स्लाइड की मार्जिन या किनारे के साथ संरेखित करता है<br/>            या उन्हें आपस में सापेक्ष रूप से संरेखित करता है। |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/hi/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | समूह आकृति के भीतर चयनित आकृतियों की स्थिति बदलता है। आकृतियों को स्लाइड की मार्जिन या किनारे के साथ संरेखित करता है<br/>            या उन्हें आपस में सापेक्ष रूप से संरेखित करता है। |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/hi/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | निर्दिष्ट स्लाइड पर सभी आकृतियों को खोजता है जो दिए गए प्लेसहोल्डर प्रकार से मेल खाते हैं। |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/hi/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | प्रस्तुति में दिए गए स्वरूप के साथ पाठ को खोजता और बदलता है। |
| [`get_all_text_boxes(slide)`](/slides/python-net/hi/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | PPTX प्रस्तुति में एक स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है। |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/hi/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | निर्दिष्ट स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है जिनमें दिया गया पाठ शामिल है। |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/hi/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | PPTX प्रस्तुति में सभी टेक्स्ट फ्रेम लौटाता है। |
| [`to_save_format(format)`](/slides/python-net/hi/aspose.slides.util/slideutil/to_save_format/#sourceformat) | स्रोत फ़ाइल फ़ॉर्मेट को संबंधित [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) में परिवर्तित करता है। |

### देखें
* मॉड्यूल [`aspose.slides.util`](/slides/python-net/hi/aspose.slides.util)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)