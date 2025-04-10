# Django Blog Project

This is a fully functional blog application built with Django. It includes features such as post creation, tagging, comments, search functionality, RSS feeds, and more.

## Features

- **Post Management**: Create, edit, and delete blog posts.
- **Tagging**: Add tags to posts for better categorization.
- **Comments**: Allow users to comment on posts.
- **Search**: Full-text search functionality using PostgreSQL.
- **RSS Feeds**: Subscribe to the latest posts via RSS.
- **Pagination**: Paginate posts for better navigation.
- **Email Sharing**: Share posts via email.
- **Sitemaps**: Automatically generated sitemaps for SEO.
- **Markdown Support**: Render post content using Markdown.


## Requirements

- Python 3.11 or higher
- Django 5.1 or higher
- PostgreSQL
- Additional Python packages:
  - `django-taggit`
  - `django-decouple`

Usage
- Admin Panel: Access the admin panel at /admin/ to manage posts, comments, and tags.
- Blog: Visit /blog/ to view the list of posts.
- Search: Use the search functionality at /blog/search/ to find posts.
- RSS Feed: Subscribe to the RSS feed at /blog/feed/.
- Sitemap: Access the sitemap at /sitemap.xml.
