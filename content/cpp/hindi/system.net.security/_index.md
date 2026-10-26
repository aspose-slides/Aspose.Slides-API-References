---
title: "System::Net::Security"
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: 
type: docs
weight: 716
url: /hi/system.net.password/
---
## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | स्ट्रीम के माध्यम से प्रमाणपत्र पास करने के लिए विधियों को समाहित करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके विन्यस्त किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनायें, क्योंकि इससे रनटाइम त्रुटियाँ और/या आश्वासन त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें। |
| [SslStream](./sslstream/) | सर्वर को प्रमाणित करने और वैकल्पिक रूप से क्लाइंट को प्रमाणित करने के लिए SSL प्रोटोकॉल का उपयोग करने वाली एक स्ट्रीम। |
## एनम्स

| एनम | विवरण |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest-विशिष्ट प्रमाणीकरण फ़्लैग। |
| [SslPolicyErrors](./sslpolicyerrors/) | SSL की नीति त्रुटियों को दर्शाता है। |
| [EncryptionPolicy](./encryptionpolicy/) | एन्क्रिप्शन नीतियों को दर्शाता है। |
## टाइपडैफ़्स

| टाइपडैफ़ | विवरण |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | रिमोट SSL प्रमाणपत्र को सत्यापित करने के लिए उपयोग किया जाने वाला उपयोगकर्ता प्रतिनिधि। |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | स्थानीय SSL प्रमाणपत्र चुनने के लिए उपयोग किया जाने वाला उपयोगकर्ता प्रतिनिधि।