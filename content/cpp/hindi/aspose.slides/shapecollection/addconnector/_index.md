---
title: AddConnector()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिफ़ॉल्ट टेम्प्लेट शैली के साथ एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 417
url: /hi/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) विधि


डिफ़ॉल्ट टेम्प्लेट शैली के साथ एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | जोड़ने के लिए कनेक्टर आकार का [ShapeType](../../shapetype/)। |
| x | **float** | कनेक्टर के फ़्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | कनेक्टर के फ़्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | कनेक्टर के फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर के फ़्रेम की ऊँचाई, पॉइंट्स में। |

### रिटर्न वैल्यू

नया बनाया गया [IConnector](../../iconnector/)।

## टिप्पणियाँ



निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](../../presentation/) में दो आकारों (एक दीर्घवृत्त और एक आयत) के बीच एक कनेक्टर (एक मुड़ा हुआ कनेक्टर) कैसे जोड़ें। 
```cpp
// एक प्रस्तुति क्लास का उदाहरण बनाता है जो PPTX फ़ाइल का प्रतिनिधित्व करती है
auto input = System::MakeObject<Presentation>();

// एक विशिष्ट स्लाइड के लिए शेप्स संग्रह तक पहुंचता है
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// एक एलिप्स ऑटोशेप जोड़ता है
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// एक रेक्टेंगल ऑटोशेप जोड़ता है
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// स्लाइड शेप्स संग्रह में एक कनेक्टर शेप जोड़ता है
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// कनेक्टर का उपयोग करके शेप्स को जोड़ता है
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// reroute को कॉल करता है जो शेप्स के बीच स्वचालित सबसे छोटा मार्ग सेट करता है
connector->Reroute();

// प्रस्तुति को सहेजता है
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) विधि


डिफ़ॉल्ट टेम्प्लेट शैली को वैकल्पिक रूप से लागू करते हुए एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | बनाने के लिए कनेक्टर आकार का [ShapeType](../../shapetype/)। |
| x | **float** | कनेक्टर के फ़्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | कनेक्टर के फ़्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | कनेक्टर के फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर के फ़्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | **bool** | डिफ़ॉल्ट टेम्प्लेट शैली (रिक्त नहीं नाम, साधारण शैली) लागू करने के लिए true; कनेक्टर को डिफ़ॉल्ट प्रॉपर्टी मानों के साथ बनाने के लिए false। |

### रिटर्न वैल्यू

नया बनाया गया [IConnector](../../iconnector/)।

## संबंधित देखें

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)