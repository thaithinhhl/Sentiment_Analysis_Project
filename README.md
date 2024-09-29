# Sentiment_Analysis_Project
# Phân tích cảm xúc khách hàng 
1. Làm sạch Data
   - Mở rộng các từ viết tắt, loại bỏ emoji và các biểu tượng
   - Thêm khoảng trắng sau dấu chấm,...
   - Loại bỏ các dấu câu -> chuyển thành chữ thường
   - Loại bỏ URL
   - Stemming và loại bỏ stopwords
2. Biểu diễn dữ liệu
3. Embedding
   - Chuyển văn bản -> vecto sử dụng kĩ thuật TD-IDF
4. Đánh giá bằng các mô hình khác nhau
   - RandomForestClassifier: Accuracy - 0.8443
   - AdaBoost: Acuracy - 0.799
   - Gradient Boosting: Accuracy - 0.8019
   - XGBoost: Acuracy - 0.8441
