# crawl_data
## Crawl dữ liệu từ trang tiki dùng scrapy

Thư mục crawl_data/crawl_image
chạy lệnh `scrapy crawl crawl_products -o product.json` để crawl dữ liệu

### Nếu muốn thay đổi số lượng sản phẩm thì vào file *crawl_image/spiders/crawl_image.py*

Thêm link crawl dòng 11

Chỉnh số lượng trang dòng 31 `url_next_page.find('page=10')`

Tham khảo thêm trên trang Scrapy Tutorial
