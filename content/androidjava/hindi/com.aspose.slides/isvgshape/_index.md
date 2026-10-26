---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options for SVG shape.
type: docs
url: /hi/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

SVG आकार के लिए विकल्पों का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | आकृति के लिए इवेंट हैंडलर सेट करता है |
| [getId()](#getId--) | आकृति के लिए id सेट या प्राप्त करता है |
| [setId(String value)](#setId-java.lang.String-) | आकृति के लिए id सेट या प्राप्त करता है |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```


आकृति के लिए इवेंट हैंडलर सेट करता है

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| eventType | int | इवेंट का प्रकार। |
| handler | java.lang.String | इवेंट को संभालने के लिए जावास्क्रिप्ट फ़ंक्शन। शून्य मान हैंडलर को हटाता है। |

### getId() {#getId--}
```
public abstract String getId()
```


आकृति के लिए id सेट या प्राप्त करता है

**वापसी:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


आकृति के लिए id सेट या प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |