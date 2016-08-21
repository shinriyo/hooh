# Hooh

To start your Phoenix app:

  1. Install dependencies with `mix deps.get`
  2. Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  3. Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix


### Redmine Demo

https://my.redmine.jp/demo/

## Initialize

まず

```
npm install -g brunch
npm install
```

もしかしたら必要
```
brunch build
```

### User
mix phoenix.gen.html User users name:string email:string password:string

### Project

mix phoenix.gen.html Project projects has_many :comments, MyApp.Comment, on_delete: :fetch_and_delete

attachment.rb	Don't force download of PDF (#22483).	3 months ago
auth_source.rb	Use safe_attributes for auth sources.	a month ago
auth_source_ldap.rb	Updates copyright for 2016.	5 months ago
board.rb	Forum list can be reordered with drag and drop (#12909).	4 months ago
change.rb	Updates copyright for 2016.	5 months ago
changeset.rb	Updates copyright for 2016.	5 months ago
comment.rb	Updates copyright for 2016.	5 months ago
custom_field.rb	Use safe_attributes for custom fields.	a month ago
custom_field_enumeration.rb	Use safe_attributes for custom field enumerations.	a month ago
custom_field_value.rb	Updates copyright for 2016.	5 months ago
custom_value.rb	Updates copyright for 2016.	5 months ago
document.rb	Updates copyright for 2016.	5 months ago
document_category.rb	Updates copyright for 2016.	5 months ago
document_category_custom_field.rb	Updates copyright for 2016.	5 months ago
document_custom_field.rb	Updates copyright for 2016.	5 months ago
email_address.rb	Use safe_attributes for email addresses.	a month ago
enabled_module.rb	Updates copyright for 2016.	5 months ago
enumeration.rb	Replaces acts_as_list with an implementation that handles #position= …	4 months ago
group.rb	Validate status of users and groups.	4 months ago
group_anonymous.rb	Updates copyright for 2016.	5 months ago
group_builtin.rb	Updates copyright for 2016.	5 months ago
group_custom_field.rb	Updates copyright for 2016.	5 months ago
group_non_member.rb	Updates copyright for 2016.	5 months ago
import.rb	CSV import delimiter detection broken (#22583).	4 months ago
import_item.rb	Updates copyright for 2016.	5 months ago
issue.rb	Issue#editable_custom_field_values very slow for issues with many cus…	21 hours ago
issue_category.rb	Updates copyright for 2016.	5 months ago
issue_custom_field.rb	Use safe_attributes for custom fields.	a month ago
issue_import.rb	Make Status map-able for CSV import (#22951).	3 months ago
issue_priority.rb	Updates copyright for 2016.	5 months ago
issue_priority_custom_field.rb	Updates copyright for 2016.	5 months ago
issue_query.rb	Make time entries groupable (#16843).	a month ago
issue_relation.rb	Updates copyright for 2016.	5 months ago
issue_status.rb	Use safe_attributes for issue statuses.	a month ago
journal.rb	Use .distinct instead of .uniq.	a month ago
journal_detail.rb	Updates copyright for 2016.	5 months ago
mail_handler.rb	Ability to define a default assigned_to when receiving emails (#23020).	2 months ago
mailer.rb	Don't send a notification to the dummy email address of the default a…	4 months ago
member.rb	Don't use add_on_empty.	a month ago
member_role.rb	Updates copyright for 2016.	5 months ago
message.rb	Updates copyright for 2016.	5 months ago
news.rb	Updates copyright for 2016.	5 months ago
principal.rb	Validate status of users and groups.	4 months ago
project.rb	Don't pass conditions to #delete_all.	a month ago
project_custom_field.rb	Updates copyright for 2016.	5 months ago
query.rb	Adds issue tracker and status columns and filters on spent time list …	22 hours ago
repository.rb	Use .distinct instead of .uniq.	a month ago
role.rb	Use safe_attributes.	a month ago
setting.rb	Don't error if an invalid setting is given.	a month ago
time_entry.rb	Updates copyright for 2016.	5 months ago
time_entry_activity.rb	Updates copyright for 2016.	5 months ago
time_entry_activity_custom_field.rb	Updates copyright for 2016.	5 months ago
time_entry_custom_field.rb	Updates copyright for 2016.	5 months ago
time_entry_query.rb	Adds issue tracker and status columns and filters on spent time list …	22 hours ago
token.rb	Updates copyright for 2016.	5 months ago
tracker.rb	Use safe_attributes.	a month ago
user.rb	Handle admin and login with safe_attributes.	a month ago
user_custom_field.rb	Updates copyright for 2016.	5 months ago
user_preference.rb	Use safe_attributes for user preferences.	a month ago
version.rb	2 spaces instead of a tab.	2 months ago
version_custom_field.rb	Updates copyright for 2016.	5 months ago
watcher.rb	Updates copyright for 2016.	5 months ago
wiki.rb	Updates copyright for 2016.	5 months ago
wiki_content.rb	Adds attachments accessor to WikiContent::Version (#23242).	a month ago
wiki_page.rb	Updates copyright for 2016.	5 months ago
wiki_redirect.rb	Updates copyright for 2016.	5 months ago
workflow_permission.rb	Don't pass conditions to #destroy_all.	a month ago
workflow_rule.rb	Don't pass conditions to #delete_all.	a month ago
workflow_transition.rb	Updates copyright for 2016.	5 months ago
