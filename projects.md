# Projects

## Jazz Song Generator

[Repo](https://github.com/yscmark/jazz-song-generator)
This project calls Spotify's api in Spring; here's a snippet:

```
public SpotifyService(WebClient.Builder webClientBuilder) {
    this.accountsClient = webClientBuilder.baseUrl("https://accounts.spotify.com")
                                         .build();
	this.apiClient = webClientBuilder.baseUrl("https://api.spotify.com/v1")
                                         .build();
}
```

## Turing Machine Model for Acceptance

Email for more information

[Return to homepage](index.md)
