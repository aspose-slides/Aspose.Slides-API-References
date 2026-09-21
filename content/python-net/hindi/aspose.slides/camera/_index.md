---
title: Camera class
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API Reference
description: 
type: docs
url: /hi/aspose.slides/camera/
---
## Camera क्लास

Camera का प्रतिनिधित्व करता है।

**विरासत:**[`Camera`](/slides/python-net/hi/aspose.slides/camera) → [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)

Camera प्रकार निम्न सदस्य प्रदर्शित करता है:

## गुण

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/hi/aspose.slides/camera/camera_type/) | Camera प्रकार.<br/>            पढ़ें/लिखें [`CameraPresetType`](/slides/python-net/hi/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/hi/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180 deg, दृश्य क्षेत्र).<br/>            पढ़ें/लिखें **float**. |
| [`zoom`](/slides/python-net/hi/aspose.slides/camera/zoom/) | Camera zoom (प्रतिशत में सकारात्मक मान).<br/>            पढ़ें/लिखें **float**. |
| [`slide`](/slides/python-net/hi/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/camera/presentation/) |  |

## विधियाँ

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/hi/aspose.slides/camera/set_rotation/#float-float-float) | एक घूर्णन को अक्षांश<br/>            निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर क्रांति के उपयोग द्वारा परिभाषित किया जाता है <br/>            जैसा कि अक्षांश और देशांतर निर्देशांक।<br/>            यदि किसी भी निर्देशांक मान में float.NaN है, तो सभी घूर्णन अपरिभाषित है. |
| [`get_rotation(self)`](/slides/python-net/hi/aspose.slides/camera/get_rotation/#) | एक घूर्णन को अक्षांश<br/>            निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर क्रांति के उपयोग द्वारा परिभाषित किया जाता है <br/>            जैसा कि अक्षांश और देशांतर निर्देशांक।<br/>            रिटर्न एरे में पहला तत्व - अक्षांश, दूसरा - देशांतर, तीसरा - क्रांति।<br/>            यदि कोई घूर्णन परिभाषित नहीं है तो None लौटाता है. |

### संबंधित देखें
* क्लास [`Camera`](/slides/python-net/hi/aspose.slides/camera)
* क्लास [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)