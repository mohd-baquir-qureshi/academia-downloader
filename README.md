
# Academia Document Downloader


This is a free unofficial API to download documents from academia.edu.


## API Reference

#### Fetch Document

```
  GET https://academia.x007.workers.dev/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. Docuement ID |

#### Fetch Document Example

Example URL - https://www.academia.edu/31982818/Ddos_protection_by_cloudflare_ray (In this "31982818" is the document ID)

```
  GET https://academia.x007.workers.dev/?id=31982818
```

```
File will be sent in response.
```

Made with ❤️ in India.
