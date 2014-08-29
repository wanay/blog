---
layout: post
title: "Hello Javascript"
date: 2014-08-29 13:29:38 +0630
comments: true
categories: Javascript
---

Javascript ကို ၁၉၉၅ ခုနစ် မေလ မှာ  [Brendan Eich](https://brendaneich.com/) က Netscape web browser အတွက် စတင် တီထွင်ခဲ့ပါတယ်။(အခုတော့ Mozilla ဖြစ်သွားပါပြီ။)စစခြင်းမှာတော့  Mocha လို့နာမည်ပေးခဲ့ပါတယ်။စက်တင်ဘာလောက်မှာတော့ LiveScript ဆိုပြီးနာမည်ထပ် ပြောင်းခဲ့ပါတယ်။အဲဒီနောက် ဒီဇင်ဘာမှာတော့ Sun ရဲ့ လိုင်စင် trademark ကိုယူပြီး Javascript ဆိုပြီးဖြစ်လာ ခဲ့ပါတယ်။Javascript က Object Oriented ဖြစ်တဲ့ Scripting Language တစ်ခုဖြစ်ပါတယ်။ဒီနေရာမှာတော့ အကျယ်မရှင်းတော့ပါဘူး။နောက်အခန်းတွေကျမှ တစ်ဖြည်းဖြည်းနားလည်လာလိမ့်မယ်။ အခုတော့ Hello World  program လေးကနေ ပဲစကြတာပေါ့။Javascript ကို Html ထဲမှာ ထည့်သွင်းအသုံးပြုဖို့

```javascript
<script type="text/javascript">
 
/* code here */
 
</script>
```

ထဲမှာသုံးပြီးရေးပါတယ်။

```javascript
<script type="text/javascript">
 
document.write("Hello World");
 
</script>
```

အဲဒါကို run လိုက်ရင် Hello World ဆိုတာကို browser မှာမြင်ရမှာပါ။
ဆိုတာက client ကို output ထုတ်ပြချင်တဲ့အခါမှာသုံးပါတယ်။နောက် javascript code တွေထဲမှာလည်း Html tag တွေထည့်ရေးလို့ရပါတယ်။
```javascript	
<!doctype html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <title>Hello World</title>
</head>
<body>
 <script type="text/javascript">
 document.write("<h1><i><u>Hello World</u></i></h1>");
 </script>
</body>
</html>
```

နောက်ပြီးကျွန်တော်တို့ Browser မှာ output ထုတ်ပြတဲ့အခါမှာ
```	
document.write("");
```
ချည်းပဲပြပေးလိုက်ရင်လိုင်းတစ်လိုင်းထဲမှာ အများကြီးဖြစ်သွားနိုင်ပါတယ်။အဲဒါကြောင့်

```	
document.writeln("");
```
ထည့်ပြီးစမ်းကြည့်လိုက်ရင်အခုလိုတွေ့ရမှာပါ။
{% codeblock index.html %}
<!doctype html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <title>Hello World</title>
</head>
<body>
 <script type="text/javascript">
 document.write("<h1><i><u>Hello World</u></i></h1>");
 document.writeln("<h2>Let's learn javascript happily</h2>");
 </script>
</body>
</html>
 {% endcodeblock %}
အခုလောက်ဆိုသဘောပေါက်လောက်မယ်ထင်ပါတယ်။အခုမှအစဆိုတော့နည်းနည်း
ချင်းပဲဆက်သွားကြရအောင်ပါ။ :)




