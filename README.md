# Moloni API collection

This [useBruno](https://docs.usebruno.com/) collection provides an easy way to try and interac with Moloni REST API.

## How to Open a Collection in useBruno

This guide provides step-by-step instructions on how to open a collection in useBruno for Moloni API testing and development.

### Step 1: Install useBruno

1. **Ensure you have useBruno installed on your system.**
    - Navigate to useBruno [download page](https://www.usebruno.com/downloads) and download the appropriate version. 
    - Choose the preferred installation method.
    - Open useBruno after installation.

### Step 2: Download Moloni collection

1. **Download files**:
    - Clone this repository or use the "Download ZIP" tool to download the files.

### Step 3: Access the Collections Page

1. **Navigate to Collections**:
    - On the left-hand sidebar of the useBruno interface, click on the "Collections" icon. This will take you to the Collections page.

### Step 4: Open the Moloni Collection

1. **Open the Collection**:
    - In the Collections page, you will see a list of available collections. Click on the "Open collection" button and locate the downloaded/cloned collection files.
2. **Expand Collection Contents**:
    - Once you click on the collection, it will expand to show the folders and requests it contains.

### Step 5: Configure the Moloni Collection

1. **Configure your .env**
    - Create a .env file in the collection root folder. The required variables can be copied from the .env.example file located in the same location.
2. **Select the environment**:
    - Select the included environment called "production". This can be done in the top right section of the bruno IDE (while selecting a request).
3. **Obtain access tokens**:
    - Execute the "grant" request located in the "authentication" folder. The access token will automatically be added to the "access_token" environment variable. 
   
### Step 6: Start Using the Moloni Collection

1. **Select a Request**:
    - Click on any request in the collection to open it in the editor.
2. **Configure and Send Requests**:
    - You can now configure the request parameters, headers, and body as needed.
    - Click on the "Send" button to make API calls and view the responses.
3. **Edit and Save**:
    - Make any necessary changes to the requests and save them within the collection.

By following these steps, you can import and start using your collections in useBruno, facilitating efficient development and testing with Moloni API.

## Contributing

We welcome contributions! You are encouraged to submit pull requests or open issues at your convenience.