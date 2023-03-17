Env Vars ၃ ခုဖြည့်ရပါမယ် စာလုံးမှားလို့မရပါ
- Name                  -(Type)-              Value
- BOT_TOKEN             -(Plaintext)-         https://t.me/BotFather မှ token ထည့်ပါ
- USE_SERVICE_ACCOUNTS  -(Plaintext)-         True သို့မဟုတ် False ထည့်ရန်။ SA ပါလျှင် True
- MAIN                   -(Plaintext)-         https://www.~~~~~~~/MAIN.zip ထည့်ရန်
  

# MAIN variable ဘယ်လိုလုပ်ရမလဲ

Service accounts သုံးမယ်ဆိုလျှင် (0-99.json) ဖိုင်များပါသော ၁။ accounts ဖိုလ်ဒါ  
၂။ token.pickle ဖိုင်
၃။ credentials.json ဖိုင်

ဒီ 3ခု (folder 1 + files 2) ကို select ပြီး zip ပါ။ Name ကို  **MAIN.zip** လို့ပေးပါ။ တခြားနာမည်ဆို Bot က မဖတ်ပါ။

MAIN.zip ဖိုင်ကို မိမိ google drive ရှိ mydrive တွင်တင်ပါ။
ထို ဖိုင်ကို " share with anyone with link " ဖြင့် share link ယူပါ။
ထို share link ကို http://gist.github.com တွင် paste ပါ file name ကို MAIN.zip လို့ပဲ ပေးပါ။
ထို့နောက် create secret gist ကို နှိပ်ပါ။ ပြီးလျှင် ညာဖက် အပေါ်နားက Raw ကို နှိပ်ပါ။
✅ထို ရလာသော link ကို အပေါ်က MAIN ရဲ့ vars မှာ ဖြည့်ပါ။


ပြီးလျှင် koyeb deploy process ဆက်သွားပါ။

# Render တွင် free host သုံးမယ်

heroku ေနာက်ပိုင်း free ရတဲ့ အဆင်ပြေတဲ့ service ပါ။
mail တစ်ခုရှိရင် အကောင့်ဖွင့်လို့ရပါပြီ။ Card မလိုပါ။

deploy guide : [Click Here](https://telegra.ph/DeployGcloneonRender-01-12)
