you can edit this app easily. 
to change the directory where you want to manage the files, ->

go to line 40
if __name__ == "__main__":
    print("Deskstop cleaner script")
    folder_path = '/Users/URUSER/Downloads' <--------
    if os.path.isdir(folder_path):
        clean_folder(folder_path)
        print("Cleaning complete")
    else: 
        print("Invalid folder path.")




then you change the directory you want and then the app (which is in the dist folder, will create new files and name them base on their language.).
