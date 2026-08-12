---
title: Replace()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: स्ट्रिंग में regex के सभी मेलों को प्रतिस्थापन स्ट्रिंग से बदलता है।
type: docs
weight: 92
url: /hi/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String&, const String&) विधि


सभी regex मेलों को प्रतिस्थापन स्ट्रिंग के साथ स्ट्रिंग में बदलता है।

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| replacement | const [String](../../../system/string/)& | प्रतिस्थापन स्ट्रिंग। |

### वापसी मान

सभी regex मेलों को प्रतिस्थापन स्ट्रिंग से बदली गई इनपुट स्ट्रिंग।

## Regex::Replace(const String&, const char_t *) विधि


सभी regex मेलों को प्रतिस्थापन स्ट्रिंग के साथ स्ट्रिंग में बदलता है।

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| replacement | const char_t * | प्रतिस्थापन स्ट्रिंग। |

### वापसी मान

सभी regex मेलों को प्रतिस्थापन स्ट्रिंग से बदली गई इनपुट स्ट्रिंग।

## Regex::Replace(const String&, const MatchEvaluator&) विधि


स्ट्रिंग में सभी मेलों को डेलीगेट द्वारा उत्पन्न प्रतिस्थापन स्ट्रिंग्स से बदलता है।

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| evaluator | const [MatchEvaluator](../../matchevaluator/)& | मेलों के आधार पर प्रतिस्थापन स्ट्रिंग्स उत्पन्न करने वाला डेलीगेट। |

### वापसी मान

सभी मेलों को बदली गई इनपुट स्ट्रिंग्स।

## Regex::Replace(const String&, const MatchEvaluator&, int) विधि


स्ट्रिंग में सभी मेलों को डेलीगेट द्वारा उत्पन्न प्रतिस्थापन स्ट्रिंग्स से बदलता है।

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| evaluator | const [MatchEvaluator](../../matchevaluator/)& | मेलों के आधार पर प्रतिस्थापन स्ट्रिंग्स उत्पन्न करने वाला डेलीगेट। |
| count | int | प्रतिस्थापनों की सीमा की संख्या। |

### वापसी मान

सभी मेलों को बदली गई इनपुट स्ट्रिंग्स।

## Regex::Replace(const String&, const MatchEvaluator&, int, int) विधि


स्ट्रिंग में सभी मेलों को डेलीगेट द्वारा उत्पन्न प्रतिस्थापन स्ट्रिंग्स से बदलता है।

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| evaluator | const [MatchEvaluator](../../matchevaluator/)& | मेलों के आधार पर प्रतिस्थापन स्ट्रिंग्स उत्पन्न करने वाला डेलीगेट। |
| count | int | प्रतिस्थापनों की सीमा की संख्या। |
| startat | int | [Index](../../../system/index/) इनपुट स्ट्रिंग में प्रतिस्थापन शुरू करने के लिए। |

### वापसी मान

सभी मेलों को बदली गई इनपुट स्ट्रिंग्स।

## Regex::Replace(const String&, const String&, int) विधि


स्ट्रिंग में उपस्ट्रिंग को बदलता है। लागू नहीं किया गया।

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String&, const String&, int, int) विधि


स्ट्रिंग में उपस्ट्रिंग को बदलता है। लागू नहीं किया गया।

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String&, const char_t *, const char_t *) विधि


सभी regex मेलों को प्रतिस्थापन स्ट्रिंग के साथ स्ट्रिंग में बदलता है।

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| pattern | const char_t * | [Regex](../) पैटर्न। |
| replacement | const char_t * | प्रतिस्थापन स्ट्रिंग। |

### वापसी मान

सभी regex मेलों को प्रतिस्थापन स्ट्रिंग से बदली गई इनपुट स्ट्रिंग।

## Regex::Replace(const String&, const String&, const char_t *) विधि


सभी regex मेलों को प्रतिस्थापन स्ट्रिंग के साथ स्ट्रिंग में बदलता है।

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| pattern | const [String](../../../system/string/)& | [Regex](../) पैटर्न। |
| replacement | const char_t * | प्रतिस्थापन स्ट्रिंग। |

### वापसी मान

सभी regex मेलों को प्रतिस्थापन स्ट्रिंग से बदली गई इनपुट स्ट्रिंग।

## Regex::Replace(const String&, const String&, const MatchEvaluator&, RegexOptions) विधि


स्ट्रिंग में सभी मेलों को डेलीगेट (स्थैतिक फ़ंक्शन) द्वारा उत्पन्न प्रतिस्थापन स्ट्रिंग्स से बदलता है।

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| pattern | const [String](../../../system/string/)& | [Regex](../) पैटर्न। |
| evaluator | const [MatchEvaluator](../../matchevaluator/)& | मेलों के आधार पर प्रतिस्थापन स्ट्रिंग्स उत्पन्न करने वाला डेलीगेट। |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) विकल्प। |

### वापसी मान

सभी मेलों को बदली गई इनपुट स्ट्रिंग्स।

## Regex::Replace(const String&, const String&, const String&, RegexOptions) विधि


सभी regex मेलों को प्रतिस्थापन स्ट्रिंग के साथ स्ट्रिंग में बदलता है।

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| pattern | const [String](../../../system/string/)& | [Regex](../) पैटर्न। |
| replacement | const [String](../../../system/string/)& | प्रतिस्थापन स्ट्रिंग। |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) विकल्प। |

### वापसी मान

सभी regex मेलों को प्रतिस्थापन स्ट्रिंग से बदली गई इनपुट स्ट्रिंग।

## Regex::Replace(const String&, const String&, const String&) विधि


regex मेलों को बदलता है।

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| pattern | const [String](../../../system/string/)& | Regexp पैटर्न। |
| replacement | const [String](../../../system/string/)& | प्रतिस्थापन स्ट्रिंग। |

### वापसी मान

[String](../../../system/string/) सभी मेलों के साथ प्रतिस्थापित।

## Regex::Replace(const String&, const String&, const MatchEvaluator&) विधि


regex मेलों को बदलता है।

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | इनपुट स्ट्रिंग। |
| pattern | const [String](../../../system/string/)& | Regexp पैटर्न। |
| evaluator | const [MatchEvaluator](../../matchevaluator/)& | प्रत्येक मेल के लिए प्रतिस्थापन स्ट्रिंग उत्पन्न करने वाला डेलीगेट। |

### वापसी मान

[String](../../../system/string/) सभी मेलों के साथ प्रतिस्थापित।

## साथ में देखें

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)