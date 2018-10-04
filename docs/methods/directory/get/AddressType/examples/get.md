[Работа со справочниками](../../../index.md)
=========================================

### ![GET](../../../../../img/get.png) [/directory/get/Gender](../index.md)

### Examples

**URI** GET `GET http://tempurl.com/directory/get/AddressType HTTP/1.1`

**Response**
```json
{
    "result":[
        {
            "id":"HP",
            "caption":"Адрес регистрации"
        },
        {
            "id":"H",
            "caption":"Адрес фактического проживания"
        },
        {
            "id":"NULL",
            "caption":"Адрес места рождения"
        },
        {
            "id":"WP",
            "caption":"Служебный адрес"
        },
        {
            "id":"DIR",
            "caption":"Прямой почтовый или телекоммуникационный адрес рабочего места"
        },
        {
            "id":"PUB",
            "caption":"Общий почтовый или телекоммуникационный адрес рабочего места"
        },
        {
            "id":"BAD",
            "caption":"Неправильный адрес"
        },
        {
            "id":"TMP",
            "caption":"Временный адрес"
        },
        {
            "id":"PST",
            "caption":"Адрес для писем"
        }
    ]
}
```