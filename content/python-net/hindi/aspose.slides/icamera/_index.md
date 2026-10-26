---
title: ICamera class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/icamera/
---
## ICamera क्लास

कैमरा का प्रतिनिधित्व करता है।

ICamera प्रकार निम्नलिखित सदस्य उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/hi/aspose.slides/icamera/camera_type/) | Camera type<br/>            पढ़ें/लिखें [`CameraPresetType`](/slides/python-net/hi/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/hi/aspose.slides/icamera/field_of_view_angle/) | Camera FOV (0-180 deg, field of View)<br/>            पढ़ें/लिखें **float**. |
| [`zoom`](/slides/python-net/hi/aspose.slides/icamera/zoom/) | Camera zoom (positive value in percentage)<br/>            पढ़ें/लिखें **float**. |

## विधियां

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/hi/aspose.slides/icamera/set_rotation/#float-float-float) | एक घूर्णन अक्षांश<br/>            समन्वय, एक देशांतर समन्वय, और अक्ष के चारों ओर एक क्रांति के उपयोग द्वारा परिभाषित किया जाता है<br/>            जैसा कि अक्षांश और देशांतर समन्वय हैं।<br/>            यदि किसी भी समन्वय मान float.NaN है, तो सभी घूर्णन अपरिभाषित होते हैं। |
| [`get_rotation(self)`](/slides/python-net/hi/aspose.slides/icamera/get_rotation/#) | एक घूर्णन अक्षांश<br/>            समन्वय, एक देशांतर समन्वय, और अक्ष के चारों ओर एक क्रांति के उपयोग द्वारा परिभाषित किया जाता है<br/>            जैसा कि अक्षांश और देशांतर समन्वय हैं।<br/>            रिटर्न एरे का पहला तत्व - अक्षांश, दूसरा - देशांतर, तीसरा - क्रांति।<br/>            यदि कोई घूर्णन परिभाषित नहीं है तो None लौटाता है। |


### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)