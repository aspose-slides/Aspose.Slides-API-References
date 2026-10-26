---
title: enclose method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
एक गणितीय तत्व को कोष्ठकों में संलग्न करता है

### Returns
प्रकार [`IMathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter) का गणितीय तत्व जो कोष्ठक शामिल करता है



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
एक गणितीय तत्व को निर्दिष्ट अक्षरों में संलग्न करता है जैसे कि कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में

### Returns
यदि `beginning_character` और `ending_character` None हैं, तो संबंधित गुणों को केवल मान सौंपे जाते हैं और कोई नया ऑब्जेक्ट नहीं बनाया जाता (यह उदाहरण रिटर्न करता है)। अन्यथा, Delimiter प्रकार का नया गणितीय तत्व रिटर्न करता है जिसमें निर्दिष्ट अक्षर फ्रेमिंग के रूप में शामिल होते हैं और इस [`MathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter) का उदाहरण अंदर फ्रेम किया जाता है।



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| beginning_character | **char** | आरंभिक अक्षर (आमतौर पर बायाँ ब्रैकेट) |
| ending_character | **char** | समाप्ति अक्षर (आमतौर पर दायाँ ब्रैकेट) |



### See Also
* क्लास [`IMathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/imathdelimiter)
* क्लास [`MathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)