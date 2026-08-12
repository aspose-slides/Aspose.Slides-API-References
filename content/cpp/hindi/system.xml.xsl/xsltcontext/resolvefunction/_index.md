---
title: ResolveFunction()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह एक फ़ंक्शन संदर्भ को हल करता है और एक IXsltContextFunction लौटाता है जो फ़ंक्शन का प्रतिनिधित्व करता है। IXsltContextFunction का उपयोग निष्पादन समय पर फ़ंक्शन के रिटर्न वैल्यू को प्राप्त करने के लिए किया जाता है।
type: docs
weight: 27
url: /hi/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) विधि

जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह एक फ़ंक्शन संदर्भ को हल करता है और [IXsltContextFunction](../../ixsltcontextfunction/) लौटाता है जो फ़ंक्शन का प्रतिनिधित्व करता है। [IXsltContextFunction](../../ixsltcontextfunction/) का उपयोग निष्पादन समय पर फ़ंक्शन की रिटर्न वैल्यू प्राप्त करने के लिए किया जाता है।

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | फ़ंक्शन का प्रीफ़िक्स जैसा कि [XPath](../../../system.xml.xpath/) अभिव्यक्ति में प्रकट होता है। |
| name | [String](../../../system/string/) | फ़ंक्शन का नाम। |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | समाधान किए जा रहे फ़ंक्शन के आर्गुमेंट प्रकारों की एक एरे। यह आपको समान नाम वाले मेथड्स के बीच चयन करने की सुविधा देता है (उदाहरण के लिए, ओवरलोडेड मेथड्स)। |

### रिटर्न वैल्यू

फ़ंक्शन का प्रतिनिधित्व करने वाला [IXsltContextFunction](../../ixsltcontextfunction/)।

## देखें

* एनम [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [IXsltContextFunction](../../ixsltcontextfunction/)
* क्लास [String](../../../system/string/)
* क्लास [XsltContext](../)
* नेमस्पेस [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)