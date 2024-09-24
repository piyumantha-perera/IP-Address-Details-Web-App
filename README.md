
# 🌐 IP Address Details Fetcher

A simple and elegant web application that retrieves and displays detailed information about a given IP address. This app is powered by **jQuery** and styled using **Tailwind CSS**, with API data fetched from **ipapi.co** through a CORS proxy.

## 🚀 Features

- **Real-time IP lookup**: Enter an IP address and retrieve information such as location, ISP, and timezone in real time.
- **User-friendly interface**: Responsive, modern design using Tailwind CSS.
- **Error handling**: Handles incorrect input or API failures with appropriate alerts.
- **CORS proxy integration**: Bypasses CORS restrictions using **AllOrigins** proxy for seamless API calls.

## 📂 Project Structure

```plaintext
📁 ip-address-details-fetcher/
├── index.html         # Main HTML file
├── README.md          # Project documentation
└── LICENSE            # License file
```

## 🛠️ Technologies Used

- **HTML5**: For the core structure of the web page.
- **jQuery**: To handle the API requests and manipulate the DOM.
- **Tailwind CSS**: For responsive and modern design with minimal custom styling.
- **ipapi.co API**: To fetch detailed IP address information.
- **AllOrigins**: A proxy service to overcome CORS issues.

## 🖥️ How It Works

1. The user enters a valid IP address in the input field.
2. Upon clicking the "Get IP Details" button, an AJAX call is made to the **ipapi.co** API via **AllOrigins**.
3. The API returns details about the IP, such as location, country, timezone, and organization.
4. These details are displayed dynamically on the page. If there’s an error or invalid input, an appropriate message is shown.

## ⚙️ Setup and Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ip-address-details-fetcher.git
   ```
2. Open `index.html` in your preferred web browser.

There are no additional dependencies or build processes required for this project.

## 📝 Usage Instructions

1. **Enter a valid IP address** in the input field provided.
2. Click the **Get IP Details** button.
3. View detailed information about the IP address, including:
   - **Network**
   - **City**
   - **Region**
   - **Country**
   - **Latitude and Longitude**
   - **Timezone**
   - **Organization**

### Example:

- **Input**: `8.8.8.8`
- **Output**:
  - **IP Address**: 8.8.8.8
  - **City**: Mountain View
  - **Region**: California
  - **Country**: United States
  - **Latitude**: 37.386
  - **Longitude**: -122.0838
  - **Timezone**: America/Los_Angeles
  - **Organization**: Google LLC



## 🔧 Customization

To customize or extend the app, you can modify the following:

- **API endpoint**: Change the IP lookup API or proxy service as needed.
- **Design**: Tailwind CSS makes it easy to customize the look and feel by adjusting the classes in `index.html`.
- **Validation**: Add IP format validation using regular expressions to improve user input handling.

## 🚨 Error Handling

- **Empty Input**: Alerts the user to enter a valid IP address if the field is left empty.
- **Invalid IP**: Displays an error message if the API call fails or if the IP is invalid.
- **CORS Proxy**: Uses **AllOrigins** to bypass CORS errors when making requests to the **ipapi.co** API.

