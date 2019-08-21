get "/contacts" do
  @contacts = Contact.all
  erb :index
end
