@Library('gest-global-library')_
node(label: 'mule-builder') {
  def map = [:]
    map.put('ymlFile', "xp-workshop.yaml")
    map.put('bucket',"xp-workshop.tools.mulesoft.com")
    map.put("region", "us-east-1")
    buildDocumentation(map)
}
