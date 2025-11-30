# **抖音简版“投稿”页面**

## **Project Overview**

This project is a simplified version of the **Douyin** (TikTok) post submission page, where users can create and submit posts consisting of both images and text. The app allows users to select images, add text, and apply text formatting such as hashtags, mentions, and locations. It simulates the "投稿" (post) feature of Douyin with a focus on image selection, text editing, and location tagging.

This app is built using **Android** and follows a modular approach for easy integration of additional features, such as the ability to add mock users, display a list of popular hashtags, and more.

## **Features**

### 1. **Image Selection and Display**
- Users can pick images from the gallery and view them in a **horizontal scrollable image selector**.
- The main image area updates when a user clicks on a thumbnail image.

### 2. **Text Editing**
- Users can input text into an **EditText field**.
- There is support for adding **hashtags**, **@mentions**, and predefined **popular topics**.
- The app provides a **word count** feature for text input, ensuring users are aware of the character limits.

### 3. **Mock User and Topic Selection**
- Users can choose from a list of **mock users** and **popular topics**.
- Tapping a user name will insert the user mention (`@username`) into the text field, and tapping a topic will insert a hashtag (`#topic`).

### 4. **Location Information**
- The app can **auto-detect the current location** using the device’s GPS and display it in the post.
- It shows the user's **city** (using longitude and latitude coordinates).

### 5. **Image Reordering**
- Users can reorder the images in the gallery before submitting their post (feature to be enhanced in future versions).
- Image deletion functionality is also supported.

## **Technologies Used**

- **Language**: Kotlin
- **Android SDK**: For app development
- **RecyclerView**: To display the list of image thumbnails.
- **BottomSheetDialog**: To select users and topics from a bottom sheet.
- **Google Maps API (Optional for future)**: For location-based services (fetching the city based on GPS coordinates).
- **ImagePicker**: For selecting images from the gallery.
- **Material Design**: UI components like buttons, text fields, etc.

## **Setup and Installation**

### **Clone the Repository**

```bash
git clone <repository-url>
