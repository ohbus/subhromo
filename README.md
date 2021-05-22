# ✨ [Blog for Subhrodip Mohanta](https://blog.subho.xyz) ✨

This is a [Jekyll](https://jekyllrb.com) site using Git as a [CMS](https://en.wikipedia.org/wiki/Content_management_system).


## Develop Locally

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)

2. Install Jekyll and Bundler:

        gem install jekyll bundler

3. Install dependencies from Gemfile:

        bundle install

4. Run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

5. Run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/6093ca085ea4cb00165b8809

6. Build the site and start the Jekyll local development server

        bundle exec jekyll serve --livereload

7. Open [http://localhost:4000](http://localhost:4000) in the browser

8. 🎉
