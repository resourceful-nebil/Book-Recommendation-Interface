# Book Recommender System Using Machine Learning

This is a book recommendation system built using machine learning techniques. It recommends books based on a user's selection from a list of popular books. The system leverages a trained model to find similar books and displays the recommended titles along with their cover images.

## Live Demo

Check out the live app here:  
[Book Recommender System](https://book-recommendation-system-using-machine-learning.streamlit.app/)

## Features

- Recommend books based on selected input from the user.
- Display book cover images for the recommended books.
- Utilizes a machine learning model to find similar books.
- Simple, interactive UI built with Streamlit.

## How It Works

1. The user selects a book from a dropdown menu.
2. The app uses a pre-trained machine learning model to find similar books.
3. It fetches the book cover images and displays the recommendations in a grid layout.

## Technologies Used

- **Python**: Backend programming.
- **Streamlit**: For building the web app and user interface.
- **scikit-learn**: For the machine learning model.
- **NumPy**: For handling numerical operations.
- **pandas**: For data manipulation and fetching book data.
- **Pickle**: For loading the pre-trained model and data files.

## Installation

To run this app locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/book-recommender-system.git
   cd book-recommender-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the `model.pkl`, `book_names.pkl`, `final_rating.pkl`, and `book_pivot.pkl` files, and place them in the `artifacts` folder.

4. Run the app:
   ```bash
   streamlit run app.py
   ```

5. Access the app at `http://localhost:8501` in your web browser.

## File Structure

```bash
📦book-recommender-system
 ┣ 📂artifacts
 ┃ ┣ 📜model.pkl
 ┃ ┣ 📜book_names.pkl
 ┃ ┣ 📜final_rating.pkl
 ┃ ┗ 📜book_pivot.pkl
 ┣ 📜app.py
 ┣ 📜requirements.txt
 ┗ 📜README.md
```

- `app.py`: The main Streamlit app script.
- `requirements.txt`: Lists all the dependencies required to run the app.
- `artifacts/`: Contains the pre-trained model and data files used by the app.

## Usage

1. Open the app.
2. Choose a book from the dropdown menu.
3. View the list of recommended books and their corresponding cover images.

## Future Enhancements

- Improve the recommendation algorithm for more personalized results.
- Add more book information such as author, genre, and ratings.
- Incorporate user feedback to refine recommendations over time.

## Contributing

Contributions are welcome! If you have ideas or find bugs, feel free to submit a pull request or open an issue.

