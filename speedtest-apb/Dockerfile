FROM ansibleplaybookbundle/apb-base

LABEL "com.redhat.apb.version"="0.1.0"
LABEL "com.redhat.apb.spec"=\
"bmFtZTogc3BlZWR0ZXN0LWFwYgppbWFnZTogYW5zaWJsZXBsYXlib29rYnVuZGxlL3NwZWVkdGVz\
dC1hcGIKZGVzY3JpcHRpb246IFRoaXMgaXMgYW4gYXBiIHRoYXQgd2lsbCBkZXBsb3kgc3BlZWR0\
ZXN0CmJpbmRhYmxlOiBGYWxzZQphc3luYzogb3B0aW9uYWwKbWV0YWRhdGE6CiAgZGlzcGxheU5h\
bWU6IHNwZWVkdGVzdApwbGFuczoKICAtIG5hbWU6IGRlZmF1bHQKICAgIGRlc2NyaXB0aW9uOiBU\
aGlzIGRlZmF1bHQgcGxhbiBkZXBsb3lzIHNwZWVkdGVzdC1hcGIKICAgIGZyZWU6IFRydWUKICAg\
IG1ldGFkYXRhOiB7fQogICAgcGFyYW1ldGVyczogW10="





COPY playbooks /opt/apb/actions
COPY roles /opt/ansible/roles
RUN chmod -R g=u /opt/{ansible,apb}
USER apb
