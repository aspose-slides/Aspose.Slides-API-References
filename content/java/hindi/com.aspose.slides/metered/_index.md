---
title: Metered
second_title: Aspose.Slides for Java API संदर्भ
description: मीटरड कुंजी सेट करने के लिए मेथड प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/metered/
---
**विरासत:**
java.lang.Object
```
public class Metered
```

मीटरड कुंजी सेट करने के लिए मेथड प्रदान करता है।
## निर्माता

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | इस क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
## विधियाँ

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | मीटरड सार्वजनिक और निजी कुंजी सेट करता है। |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | उपभोग फ़ाइल आकार प्राप्त करता है |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपभोग क्रेडिट प्राप्त करता है |
| [isMeteredLicensed()](#isMeteredLicensed--) | जाँचें कि मीटरड लाइसेंस्ड है या नहीं |
### Metered() {#Metered--}
```
public Metered()
```


इस क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


मीटरड सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटरड लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू होने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। हालांकि, यदि उपभोग डेटा अपलोड करने में लगातार विफल रहते हैं और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को इवैल्युएशन स्टेटस में सेट किया जाएगा; ऐसी स्थिति से बचने के लिए आपको नियमित रूप से लाइसेंस की स्थिति जाँचनी चाहिए, यदि यह इवैल्युएशन स्टेटस है, तो इस API को फिर से कॉल करें।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | सार्वजनिक कुंजी |
| privateKey | java.lang.String | निजी कुंजी |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


उपभोग फ़ाइल आकार प्राप्त करता है

**वापसी:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


उपभोग क्रेडिट प्राप्त करता है

**वापसी:**
double - consumption quantity
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


जाँचें कि मीटरड लाइसेंस्ड है या नहीं

**वापसी:**
boolean - True या False