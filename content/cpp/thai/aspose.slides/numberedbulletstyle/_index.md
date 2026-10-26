---
title: NumberedBulletStyle
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงสไตล์ของสัญลักษณ์รายการที่มีหมายเลข.
type: docs
weight: 6124
url: /th/aspose.slides/numberedbulletstyle/
---
## NumberedBulletStyle enum


Represents the style of the numbered bullets.

```cpp
enum class NumberedBulletStyle : int8_t
```

### ค่าตัวเลือก

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| NotDefined | -1 | ไม่ได้กำหนด. |
| BulletAlphaLCPeriod | 0 | อักษรตัวพิมพ์เล็กพร้อมจุด. ตัวอย่าง: a., b., c., ... |
| BulletAlphaUCPeriod | 1 | อักษรตัวพิมพ์ใหญ่พร้อมจุด. ตัวอย่าง: A., B., C., ... |
| BulletArabicParenRight | 2 | ตัวเลขอารบิกพร้อมวงเล็บปิด. ตัวอย่าง: 1), 2), 3), ... |
| BulletArabicPeriod | 3 | ตัวเลขอารบิกพร้อมจุด. ตัวอย่าง: 1., 2., 3., ... |
| BulletRomanLCParenBoth | 4 | ตัวเลขโรมันตัวพิมพ์เล็กพร้อมวงเล็บทั้งสองด้าน. ตัวอย่าง: (i), (ii), (iii), ... |
| BulletRomanLCParenRight | 5 | ตัวเลขโรมันตัวพิมพ์เล็กพร้อมวงเล็บปิด. ตัวอย่าง: i), ii), iii), ... |
| BulletRomanLCPeriod | 6 | ตัวเลขโรมันตัวพิมพ์เล็กพร้อมจุด. ตัวอย่าง: i., ii., iii., ... |
| BulletRomanUCPeriod | 7 | ตัวเลขโรมันตัวพิมพ์ใหญ่พร้อมจุด. ตัวอย่าง: I., II., III., ... |
| BulletAlphaLCParenBoth | 8 | อักษรตัวพิมพ์เล็กพร้อมวงเล็บทั้งสองด้าน. ตัวอย่าง: (a), (b), (c), ... |
| BulletAlphaLCParenRight | 9 | อักษรตัวพิมพ์เล็กพร้อมวงเล็บปิด. ตัวอย่าง: a), b), c), ... |
| BulletAlphaUCParenBoth | 10 | อักษรตัวพิมพ์ใหญ่พร้อมวงเล็บทั้งสองด้าน. ตัวอย่าง: (A), (B), (C), ... |
| BulletAlphaUCParenRight | 11 | อักษรตัวพิมพ์ใหญ่พร้อมวงเล็บปิด. ตัวอย่าง: A), B), C), ... |
| BulletArabicParenBoth | 12 | ตัวเลขอารบิกพร้อมวงเล็บทั้งสองด้าน. ตัวอย่าง: (1), (2), (3), ... |
| BulletArabicPlain | 13 | ตัวเลขอารบิก. ตัวอย่าง: 1, 2, 3, ... |
| BulletRomanUCParenBoth | 14 | ตัวเลขโรมันตัวพิมพ์ใหญ่พร้อมวงเล็บทั้งสองด้าน. ตัวอย่าง: (I), (II), (III), ... |
| BulletRomanUCParenRight | 15 | ตัวเลขโรมันตัวพิมพ์ใหญ่พร้อมวงเล็บปิด. ตัวอย่าง: I), II), III), ... |
| BulletSimpChinPlain | 16 | ภาษาจีนตัวย่อโดยไม่มีจุด. |
| BulletSimpChinPeriod | 17 | ภาษาจีนตัวย่อพร้อมจุด. |
| BulletCircleNumDBPlain | 18 | ตัวเลขวงกลมแบบดับเบิลไบท์สำหรับค่าไม่เกิน 10, ตั้งแต่ 11 เป็นต้นไปใช้ตัวเลขอารบิก. |
| BulletCircleNumWDWhitePlain | 19 | ตัวเลขสีข้อความพร้อมวงกลมสีเดียวกันล้อมรอบ (Wingdings white circle numbers). ตั้งแต่ 11 เป็นต้นไปใช้ตัวเลขอารบิก. |
| BulletCircleNumWDBlackPlain | 20 | ตัวเลขสีเงาพร้อมพื้นหลังวงกลมสีข้อความปกติ (Wingdings black circle numbers). |
| BulletTradChinPlain | 21 | ภาษาจีนดั้งเดิมโดยไม่มีจุด. |
| BulletTradChinPeriod | 22 | ภาษาจีนดั้งเดิมพร้อมจุด. |
| BulletArabicAlphaDash | 23 | อักษรภาษาอาหรับพร้อมขีด. |
| BulletArabicAbjadDash | 24 | อักษรอาบจัดของอาหรับพร้อมขีด. |
| BulletHebrewAlphaDash | 25 | อักษรภาษาฮีบรูพร้อมขีด. |
| BulletKanjiKoreanPlain | 26 | ตัวเลขญี่ปุ่น/เกาหลีโดยไม่มีจุด. |
| BulletKanjiKoreanPeriod | 27 | ตัวเลขญี่ปุ่น/เกาหลีพร้อมจุด. |
| BulletArabicDBPlain | 28 | ระบบลำดับเลขอารบิกแบบดับเบิลไบท์ (ไม่มีเครื่องหมายวรรคตอน). |
| BulletArabicDBPeriod | 29 | ระบบลำดับเลขอารบิกแบบดับเบิลไบท์พร้อมจุดแบบดับเบิลไบท์. |
| BulletThaiAlphaPeriod | 30 | ตัวอักษรไทยพร้อมจุด. |
| BulletThaiAlphaParenRight | 31 | วงเล็บของตัวอักษรไทย - ด้านขวา. |
| BulletThaiAlphaParenBoth | 32 | วงเล็บของตัวอักษรไทย - ทั้งสองด้าน. |
| BulletThaiNumPeriod | 33 | ตัวเลขไทยพร้อมจุด. |
| BulletThaiNumParenRight | 34 | วงเล็บของตัวเลขไทย - ด้านขวา. |
| BulletThaiNumParenBoth | 35 | วงเล็บของตัวเลขไทย - ทั้งสองด้าน. |
| BulletHindiAlphaPeriod | 36 | ตัวอักษรฮินดีพร้อมจุด - สระ. |
| BulletHindiNumPeriod | 37 | ตัวเลขฮินดีพร้อมจุด. |
| BulletKanjiSimpChinDBPeriod | 38 | คันจิจีนตัวย่อ DBPeriod. |
| BulletHindiNumParenRight | 39 | วงเล็บของตัวเลขฮินดี - ด้านขวา. |
| BulletHindiAlpha1Period | 40 | ตัวอักษรฮินดีพร้อมจุด - พยัญชนะ. |

## ดูเพิ่มเติม

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)