# The Blog

# How to make a blog entry.

1. Create a directory under here.  YYYY-MM-DD, 2 underscores, title with spaces as dashes.

Example
```
2019-01-02__how-to-configure-nuvuli-aws-access
```

2. In your blog's directory, create markdown for all your content in a file called `index.md`

If you have images, css, or downloads, refer to them as `{{ basepath }}/yourfile.jpg`.  Store the file in your blog's directory.


3. In your blog's directory, create a file called `metadata.json`.  Example below, change content to taste.  All fields below are required.

```
{
    "title": "How to Configure Nuvuli for Access to your AWS Account",
    "keywords": "keywords keywords",
    "description": "description description",
    "author": "Ken Bedwell"
}
```

4. Restart cc-www in production via kubectl.  Yes, there are probably slicker ways to handle this.
