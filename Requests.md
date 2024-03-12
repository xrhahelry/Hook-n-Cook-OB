# Requests
- [Requests](https://requests.readthedocs.io/en/latest/) is a user-friendly web scraping library in Python built on top of urllib3. It can directly get a URL without a `PoolManager` instance.
- Also, once you make a `GET` request, you can access the web page's contents by using the `content` property on the response object.
- It simplifies the process of sending HTTP requests and handling responses

#### Pros
- It doesn't require `PoolManager`.
- It's fast.
- It's easily understandable.

#### Cons
- It can't scrape interactive or dynamic sites with JavaScript.
- It's not good for sensitive information as it might be retained in the browser's memory.