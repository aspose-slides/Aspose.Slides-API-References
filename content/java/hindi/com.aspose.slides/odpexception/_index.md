---
title: OdpException
second_title: Aspose.Slides for Java API संदर्भ
description: एक मानक आंतरिक अपवाद प्रकार को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/odpexception/
---
**विरासत:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

एक मानक आंतरिक अपवाद प्रकार दर्शाता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [OdpException()](#OdpException--) | डिफ़ॉल्ट निर्माता |
| [OdpException(String message)](#OdpException-java.lang.String-) | संदेश को इस अपवाद में जोड़ने की अनुमति देने वाला निर्माता। |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | एक संदेश और एम्बेडेड अपवाद युक्त अपवाद के लिए निर्माता। |

### OdpException() {#OdpException--}
```
public OdpException()
```

डिफ़ॉल्ट निर्माता

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```

संदेश को इस अपवाद में जोड़ने की अनुमति देने वाला निर्माता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | संदेश |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```

एक संदेश और एम्बेडेड अपवाद युक्त अपवाद के लिए निर्माता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | संदेश |
| exception | java.lang.RuntimeException | मूल अपवाद |