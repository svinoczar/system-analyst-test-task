# Effective Mobile (Junior System Analyst) Test Task
### Task 1
![task1 image][task1.png]
Пример REST API запроса, который будет вызываться при переходе на экран выше и пример JSON ответа:

GET запрос:
```http://market.yandex.ru/api/v1/recommendations/get``` 

Response:
```json
{
    "message": "List of goods",
    "status_code": 200,
    "timestamp": "2024-07-24T04:39:48.875024+03:00",
    "goods": [
        {
            "id": 1,
            "name": "Наручные часы CASIO Collection LTP-VT02BL-3A",
            "currency_symbol": "₽",
            "price": 4539,
            "discount_price": 3440,
            "image_refference": "/img/watches/casio/LTP-VT02BL-3A.png"

        },
        {
            "id": 2,
            "name": "Стеллаж для книг KM LOFT Ромбо черный/дуб вотан",
            "currency_symbol": "₽",
            "price": 42990,
            "discount_price": 9407,
            "image_refference": "/img/furniture/bookshelf/KM_LOFT_Ромбо_черный/дуб_вотан.png"

        },
        {
            "id": 3,
            "name": "Полка настенная ChoodWood 60x20 см из массива дерева карагач",
            "currency_symbol": "₽",
            "price": 8918,
            "discount_price": 2520,
            "image_refference": "/img/furniture/bookshelf/ChoodWood_60x20_см_карагач.png"

        },
        {
            "id": 4,
            "name": "Тумба прикроватная из МДФ Белая ноги золото 50x50x40 см",
            "currency_symbol": "₽",
            "price": 4539,
            "discount_price": 3440,
            "image_refference": "/img/furniture/bedside_cabinet МДФ_Белая_ноги_золото_50x50x40_см.png"
        }
    ]
}
```
