# `Thai-to-English Machine` Translation Model
 Machine Translation (MT) model that can translate from Thai to English which was trained on KDE4 dataset
where each pair of languages from KDE4 dataset can be accessed via : https://opus.nlpl.eu/KDE4.php
- I also have a `model weight` available and will be updated later

```
test_data = [
    "สวัสดีปีใหม่นะครับ ขอให้ปีนี้เป็นปีที่ดีสำหรับทุกคนนะ",
    "ในทุก ๆ วัน หากเราอยู่กับใครมาก ๆ จะเป็นคนในครอบครัว หรือทำงานร่วมกับใครบ่อย ๆ แล้วต้อง “เป็นฝ่ายขอบคุณเสมอ” นั่นหมายความว่าเราเป็นผู้รับจากเขามากกว่า เขาต้องช่วยเหลือเรามากกว่า เลยเถิดไปถึงว่าเราอาจทำอะไรได้ไม่ค่อยดีประจำเขาต้องช่วยประจำ มีศักยภาพน้อยเกินไป ใช่ว่าจะเป็นความผิดเสียทีเดียว",
    "ประเทศไทยมีประชากรประมาณ 60 ล้านคน"
]
     

# translation output    
[{'translation_text': 'Have a new year. Have a nice year for everybody.'},
 {'translation_text': 'On every day, if we are with one another, family members, or often working with one another, be sure to be "genuine". This means that we are more of them than they are for us. Even if there is no good in us, they are less likely to do so, and are less likely to be able to do so. This is not a sin.'},
 {'translation_text': 'Thailand has a population of 60 billion.'}]
```

<b>(the blog about machine translation will be published soon)</b>

