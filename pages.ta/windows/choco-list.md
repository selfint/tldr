# choco list

> சாக்லேட்டியுடன் ஒன்று அல்லது அதற்கு மேற்பட்ட தொகுப்புகளை நிறுவவும்.
> மேலும் விவரத்திற்கு: <https://chocolatey.org/docs/commands-install>.

- கிடைக்கக்கூடிய அனைத்து தொகுப்புகளையும் காண்பி:

`choco list`

- உள்நாட்டில் நிறுவப்பட்ட அனைத்து தொகுப்புகளையும் காண்பி:

`choco list --local-only`

- உள்ளூர் நிரல்களை உள்ளடக்கிய பட்டியலைக் காண்பி:

`choco list --include-programs`

- அங்கீகரிக்கப்பட்ட தொகுப்புகளை மட்டும் காண்பி:

`choco list --approved-only`

- இதிலிருந்து தொகுப்புகளைக் காண்பிக்க தனிப்பயன் மூலத்தைக் குறிப்பிடவும்:

`choco list --source {{மூல_முகவரி|alias}}`

- அங்கீகாரத்திற்கான பயனர்பெயர் மற்றும் கடவுச்சொல்லை வழங்கவும்:

`choco list --user {{பயனர்பெயர்}} --password {{கடவுச்சொல்}}`
