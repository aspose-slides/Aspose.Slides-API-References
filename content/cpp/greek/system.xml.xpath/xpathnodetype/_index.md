---
title: XPathNodeType
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει τους τύπους κόμβων XPath που μπορούν να επιστραφούν από την κλάση XPathNavigator.
type: docs
weight: 157
url: /el/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Ορίζει τους [XPath](../) τύπους κόμβων που μπορούν να επιστραφούν από την κλάση [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Root | 0 | Ο ριζικός κόμβος του εγγράφου XML ή του δέντρου κόμβων. |
| Element | 1 | Ένα στοιχείο, όπως **<element>**. |
| Attribute | 2 | Ένα χαρακτηριστικό, όπως **id='123'**. |
| Namespace | 3 | Ένας χώρος ονομάτων, όπως **xmlns=\"namespace\"**. |
| Text | 4 | Το κειμενικό περιεχόμενο ενός κόμβου. Ισοδύναμο με το Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) και τους τύπους κόμβων CDATA. Περιέχει τουλάχιστον έναν χαρακτήρα. |
| SignificantWhitespace | 5 | Κόμβος με χαρακτήρες λευκού διαστήματος και **xml:space** ορισμένο σε **preserve**. |
| Whitespace | 6 | Κόμβος μόνο με χαρακτήρες λευκού διαστήματος και χωρίς σημαντικό λευκό διάστημα. Οι χαρακτήρες λευκού διαστήματος είναι **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Μία οδηγία επεξεργασίας, όπως **<?pi test?>**. Αυτό δεν περιλαμβάνει δηλώσεις XML, που δεν είναι ορατές στην κλάση [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Ένα σχόλιο, όπως ****. |
| All | 9 | Οποιοσδήποτε από τους τύπους κόμβου XPathNodeType. |

## Δείτε επίσης

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)