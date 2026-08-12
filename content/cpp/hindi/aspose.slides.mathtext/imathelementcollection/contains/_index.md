---
title: Contains()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि संग्रह में कोई विशिष्ट मान मौजूद है या नहीं।
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection::Contains(System::SharedPtr\<IMathElement\>) विधि

निर्धारित करता है कि संग्रह में एक विशिष्ट मान मौजूद है या नहीं।

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Contains(System::SharedPtr<IMathElement> item)=0
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | उस वस्तु को निर्दिष्ट करता है जिसे संग्रह में खोजा जाना है। |

### रिटर्न मान

यदि *item* संग्रह में पाया जाता है तो true; अन्यथा false।

## टिप्पणी



उदाहरण: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = collection->Contains(plusElement);
```

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)