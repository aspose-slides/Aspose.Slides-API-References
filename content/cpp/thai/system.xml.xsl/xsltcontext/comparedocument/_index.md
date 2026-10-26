---
title: CompareDocument()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด จะเปรียบเทียบ Uniform Resource Identifiers (URIs) พื้นฐานของเอกสารสองฉบับตามลำดับที่เอกสารถูกโหลดโดยตัวประมวลผล XSLT (ซึ่งคือคลาส XslTransform).
type: docs
weight: 53
url: /th/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) เมธอด

When overridden in a derived class, compares the base Uniform Resource Identifiers (URIs) of two documents based upon the order the documents were loaded by the XSLT processor (that is, the [XslTransform](../../xsltransform/) class).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### อาร์กิวเมนท์

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | The base URI of the first document to compare. |
| nextbaseUri | [String](../../../system/string/) | The base URI of the second document to compare. |

### ค่าที่คืน

An integer value describing the relative order of the two base URIs: -1 if **baseUri** occurs before **nextbaseUri**; 0 if the two base URIs are identical; and 1 if **baseUri** occurs after **nextbaseUri**.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XsltContext](../)
* เนมสเปซ [System::Xml::Xsl](../../)
* ไลบรารี [Aspose.Slides](../../../)