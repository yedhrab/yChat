# 💭 yChat

Simplest telegram & SMS client that use ChatGPT ([revChatGPT](https://github.com/acheong08/ChatGPT))

```python
from ychat import yChat

if __name__ == "__main__":
    yChat().start_telegram_server()
    # yChat().start_sms_server()
```

![image](https://i.imgur.com/pYkcniq.png)

1. Fill settings.yaml file to use it
    1. Telegram token
    2. ChatGPT auth
2. When you run code settings.yaml will be created at current directory
3. Preffered method is access_token sign in ([show my access token](https://chat.openai.com/api/auth/session))


## 🚨 Disclaimers

It's not about OpenAI, it's just my personal project (I don't give any support for it)
