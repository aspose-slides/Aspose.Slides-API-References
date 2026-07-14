---
title: Metered
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: मीटरड कुंजी सेट करने के लिए मेथड्स प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/metered/
---
**विरासत:**
java.lang.Object
```
public class Metered
```

मीटरड कुंजी सेट करने के लिए मेथड्स प्रदान करता है।
## कंस्ट्रक्टर्स

| निर्माता | विवरण |
| --- | --- |
| [Metered()](#Metered--) | इस क्लास की नई इंस्टेंस को प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | मीटरड सार्वजनिक और निजी कुंजी सेट करता है। |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | उपभोग फ़ाइल आकार प्राप्त करता है |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपभोग क्रेडिट प्राप्त करता है |
| [isMeteredLicensed()](#isMeteredLicensed--) | जाँचें कि मीटरड लाइसेंसेड है या नहीं |
### Metered() {#Metered--}
```
public Metered()
```

इस क्लास की नई इंस्टेंस को प्रारंभ करता है।

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

मीटरड सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटरड लाइसेंस खरीदते हैं, एप्लिकेशन शुरू होने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। हालाँकि, यदि हमेशा उपभोग डेटा अपलोड करने में विफल रहता है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट कर दिया जाएगा, इस स्थिति से बचने के लिए आपको नियमित रूप से लाइसेंस स्थिति जांचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| publicKey | java.lang.String | सार्वजनिक कुंजी |
| privateKey | java.lang.String | निजी कुंजी |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

उपभोग फ़ाइल आकार प्राप्त करता है

**रिटर्न मान:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

उपभोग क्रेडिट प्राप्त करता है

**रिटर्न मान:**
double - उपभोग मात्रा
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

जाँचें कि मीटरड लाइसेंसेड है या नहीं

**रिटर्न मान:**
boolean - सत्य या असत्य