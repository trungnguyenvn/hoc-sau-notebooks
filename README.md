# Học Sâu · Notebooks

Notebook Jupyter đi kèm khóa học [Học Sâu · Reels](https://d3qr1cjln6qqtk.cloudfront.net/): mỗi bài một notebook,
viết bằng numpy từ đầu, chạy trên dữ liệu thật. Mọi con số trong reel và demo của bài đều do notebook tính lại và kiểm tra.

| Bài | Notebook | |
|---|---|---|
| 01 · Perceptron | [01-perceptron.ipynb](01-perceptron.ipynb) | [![Mở trong Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/trungnguyenvn/hoc-sau-notebooks/blob/main/01-perceptron.ipynb) |
| 02 · Hàm kích hoạt | [02-ham-kich-hoat.ipynb](02-ham-kich-hoat.ipynb) | [![Mở trong Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/trungnguyenvn/hoc-sau-notebooks/blob/main/02-ham-kich-hoat.ipynb) |
| 04 · Softmax & hàm mất mát | [04-ham-mat-mat.ipynb](04-ham-mat-mat.ipynb) | [![Mở trong Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/trungnguyenvn/hoc-sau-notebooks/blob/main/04-ham-mat-mat.ipynb) |
| 05 · Gradient descent | [05-gradient-descent.ipynb](05-gradient-descent.ipynb) | [![Mở trong Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/trungnguyenvn/hoc-sau-notebooks/blob/main/05-gradient-descent.ipynb) |
| 07 · Momentum, Adam & AdamW | [07-bo-toi-uu.ipynb](07-bo-toi-uu.ipynb) | [![Mở trong Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/trungnguyenvn/hoc-sau-notebooks/blob/main/07-bo-toi-uu.ipynb) |

Các bài tiếp theo sẽ được thêm dần, theo thứ tự của khóa học.

## Cách chạy

- **Colab:** bấm nút “Mở trong Colab”, rồi chọn *Runtime → Run all*. Không cần cài gì; notebook tự tải dữ liệu (MNIST, ~11 MB) và kiểm tra mã MD5.
- **Trên máy:** cần Python ≥ 3.10 với numpy, matplotlib và Jupyter:

  ```bash
  pip install numpy matplotlib jupyterlab
  jupyter lab 01-perceptron.ipynb
  ```

Notebook được kiểm thử với đúng phiên bản của Colab hiện tại (Python 3.13, numpy 2.1.3, matplotlib 3.10.0). Mỗi bài chạy
dưới 1 phút trên CPU.

Notebook không kèm output: hãy tự chạy, và trả lời các câu “🤔 Dự đoán trước” trước khi chạy ô kế tiếp.

## Giấy phép

- Mã nguồn: [MIT](LICENSE).
- Nội dung bài viết và hình vẽ: [CC BY 4.0](LICENSE-CONTENT).
- MNIST (LeCun, Cortes & Burges) không nằm trong repo; notebook tải nó lúc chạy.
