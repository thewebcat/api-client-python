retailCRM API python client
===========================

### Install

```
pip install git+https://github.com/thewebcat/api-client-python.git
```

### Usage

```python
import retailcrm


client = retailcrm.Client('https://demo.intarocrm.ru', 'uLxXKBwjQteE9NkO3cJAqTXNwvKktaTc')

order = {
  'firstName': 'Ivan',
  'lastName': 'Ivanov',
  'phone': '+79000000000',
  'email': 'ivan@example.com',
  'orderMethod': 'call-request',
}

result = client.orders_create(order)
```

### Documentation

* http://www.retailcrm.pro/docs/Developers/ApiVersion5
