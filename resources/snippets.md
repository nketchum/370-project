### LOAD CSV FROM GOOGLE DRIVE
url = 'https://drive.google.com/file/d/1g_Iok1V2NnWKBy0r9qGG7XavUlOhDzWe/view?usp=sharing'
path = 'https://drive.google.com/uc?export=download&id=' + url.split('/')[-2]
historic_arrests = pd.read_csv(path)