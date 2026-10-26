---
title: DigitalSignature class
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/digitalsignature/
---
## DigitalSignature فئة

التوقيع الرقمي في الملف الموقع.

يعرض نوع DigitalSignature الأعضاء التالية:

## المُنشئات

| المُنشئ | الوصف |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/ar/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Creates a new DigitalSignature object with the specified certificate. |
| [`__init__(self, file_path, password)`](/slides/python-net/ar/aspose.slides/digitalsignature/__init__/#str-str) | Creates a new DigitalSignature object with the specified certificate file path and password. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`certificate`](/slides/python-net/ar/aspose.slides/digitalsignature/certificate/) | كائن الشهادة الذي تم استخدامه لتوقيع المستند.<br/>            **للقراءة فقط** **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/ar/aspose.slides/digitalsignature/is_valid/) | إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند، ستكون هذه القيمة true.<br/>            **للقراءة فقط** **bool**. |
| [`sign_time`](/slides/python-net/ar/aspose.slides/digitalsignature/sign_time/) | الوقت الذي تم فيه توقيع المستند.<br/>            **للقراءة فقط** **System.DateTime**. |
| [`comments`](/slides/python-net/ar/aspose.slides/digitalsignature/comments/) | غرض التوقيع.<br/>            **قابل للقراءة والكتابة** **str**. |


### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)