# faker-ecommerce

Faker provider for generating e-commerce fake data.

## Installation

```bash
pip install faker-ecommerce
```

## Usage

```python
from faker import Faker
from faker_ecommerce import EcommerceProvider

fake = Faker()
fake.add_provider(EcommerceProvider)

fake.product_name()       # 'Premium Leather Electronics Item'
fake.sku()                # 'ABC-1234-XY'
fake.order_id()           # 'ORD-123456789'
fake.tracking_number()    # '1ZABCD1234567890'
fake.price()              # '$49.99'
fake.shipping_carrier()   # 'FedEx'
fake.payment_method()     # 'Apple Pay'
```

## Available Methods

| Method | Example |
|--------|---------|
| `product_name()` | Premium Leather Electronics Item |
| `product_category()` | Electronics, Clothing, Home & Garden |
| `sku()` | ABC-1234-XY |
| `order_id()` | ORD-123456789 |
| `tracking_number()` | 1ZABCD1234567890 |
| `price()` | $49.99 |
| `discount_percentage()` | 25% |
| `shipping_carrier()` | FedEx, UPS, DHL |
| `payment_method()` | Credit Card, PayPal, Apple Pay |
| `order_status()` | Pending, Shipped, Delivered |
| `customer_type()` | Guest, VIP, Prime |
| `return_reason()` | Wrong Size, Defective |
| `coupon_code()` | SAVE20 |
| `review_rating()` | 1-5 |

## License

MIT
